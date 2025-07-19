---
layout: post
title: System Engineering Project 1
description:  Autonomous Navigation with LIMO Robot. Developed real-time SLAM maps with RTAB-Map, implemented waypoint-based navigation, and designed a custom testing arena for evaluating path planning and obstacle avoidance. 
skills: 
  - ROS(Melodic)
  - Python

main-image: /limo.png
---

---
# Arena Design Overview

## Changi Airport Terminal 1
{% include image-gallery.html images="t1_reference.png" height="400" %}

The layout of the arena was inspired by the departure hall of Changi Airport Terminal 1, particularly the area surrounding the FAST check-in zone and boarding access gates. This environment was selected as a reference due to its structured flow, open layout, and realistic operational constraints

This design emulates a semi-structured, real-world indoor environment, which provides the ideal conditions for testing:
  - Waypoint navigation,
  - Real-time SLAM (via RTAB-Map),
  - Path planning in dynamic obstacle scenarios.

## Preliminary Arena Design 
{% include image-gallery.html images="preliminary_arena_design.png" height="400" %}

This arena was designed as a controlled environment to test autonomous navigation capabilities using the LIMO robot with ROS and RTAB-Map. The layout simulates a structured indoor space resembling a departure hall of Changi Airport Terminal 1, with deliberate inclusion of tight paths, sensory triggers and blind spots.

## Arena Design Visualized with 3D Modeling
{% include image-gallery.html images="solidwork_arena.png" height="400" %}

To support the physical planning and spatial validation of the robot navigation testbed, the preliminary 2D sketch was translated into a 3D model using SolidWorks.

## Finalize Arena Design
{% include image-gallery.html images="finalise_arena.png" height="400" %}

The final physical arena was constructed based on the initial conceptual layout and CAD visualization. It replicates a scaled-down version of a structured indoor environment — inspired by real-world airport terminals

  - Enclosed Room & Slide Zone
    Simulates interactive or dynamic zones such as baggage screening or waiting lounges.

  - Pathways and Boundaries
    White boundaries help with LiDAR and depth sensor feedback, ensuring robust obstacle detection and wall-following     capabilities.

## Embedding images 
### External images
{% include image-gallery.html images="https://live.staticflickr.com/65535/52821641477_d397e56bc4_k.jpg, https://live.staticflickr.com/65535/52822650673_f074b20d90_k.jpg" height="400"%}
<span style="font-size: 10px">"Starship Test Flight Mission" from https://www.flickr.com/photos/spacex/52821641477/</span>  
You can put in multiple entries. All images will be at a fixed height in the same row. With smaller window, they will switch to columns.  

### Embeed images
{% include image-gallery.html images="project2.jpg" height="400" %} 
place the images in project folder/images then update the file path.   


## Embedding youtube video
The second video has the autoplay on. copy and paste the 11-digit id found in the url link. <br>
*Example* : https://www.youtube.com/watch?v={**MhVw-MHGv4s**}&ab_channel=engineerguy
{% include youtube-video.html id="MhVw-MHGv4s" autoplay= "false"%}
{% include youtube-video.html id="XGC31lmdS6s" autoplay = "true" %}

you can also set up custom size by specifying the width (the aspect ratio has been set to 16/9). The default size is 560 pixels x 315 pixels.  

The width of the video below. Regardless of initial width, all the videos is responsive and will fit within the smaller screen.
{% include youtube-video.html id="tGCdLEQzde0" autoplay = "false" width= "900px" %}  

<br>

## Adding a hozontal line
---

## Starting a new line
leave two spaces "  " at the end or enter <br>

## Adding bold text
this is how you input **bold text**

## Adding italic text
Italicized text is the *cat's meow*.

## Adding ordered list
1. First item
2. Second item
3. Third item
4. Fourth item

## Adding unordered list
- First item
- Second item
- Third item
- Fourth item

## Adding code block
```ruby
def hello_world
  puts "Hello, World!"
end
```

```python
def start()
  print("time to start!")
```

```javascript
let x = 1;
if (x === 1) {
  let x = 2;
  console.log(x);
}
console.log(x);

```

## Adding external links
[Wikipedia](https://en.wikipedia.org)


## Adding block quote
> A blockquote would look great if you need to highlight something


## Adding table 

| Header 1 | Header 2 |
|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 |
| Row 2, Col 1 | Row 2, Col 2 |

make sure to leave aline betwen the table and the header


