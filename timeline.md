---
layout: page
title:  Timeline
---
 <link title="timeline-styles" rel="stylesheet" href="https://cdn.knightlab.com/libs/timeline3/latest/css/timeline.css">
<script src="https://cdn.knightlab.com/libs/timeline3/latest/js/timeline.js"></script>

<div id='timeline-embed' style="width: 100%; height: 600px"></div>


<script type="text/javascript">
            var additionalOptions = {
              start_at_end: true,
              default_bg_color: {r:0, g:0, b:0},
              timenav_height: 250
            }

            timeline = new TL.Timeline('timeline-embed',
            'timeline.json',
            additionalOptions);
</script>
