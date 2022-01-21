---
layout: default
---
### About Me

I am a Ph.D. candidate at the [Department of Computer Science and Engineering](https://cse.umn.edu/cs) at the University of Minnesota. My research focus is on guiding and control simulations of highly dynamic phenomena for computer graphics and robotics applications. Currently, I am doing my research under the supervision of [Dr. Rahul Narain](https://www.cse.iitd.ac.in/~narain/) and co-advised by [Dr. Stephen Guy](https://www-users.cse.umn.edu/~sjguy/) . previously, I got my M.Sc. in Astrophysics from the Department of Physics and Astronomy at the University of Minnesota in February 2015. My current research lies on simulating a highly dynamic phenomena, such as smoke and crowd, with control over the behavior of the system while the behavior stays natural and realistic.

<!-- ### Education

* Ph.D. Computer Science, Expected May 2022
	* Thesis: Guiding Simulation of Highly Dynamic Phenomena
	* Advisors: Dr.Rahul Narain, Dr.Stephen Guy	


* M.Sc. Astrophysics, February 2016
	* Thesis: The Radio Luminosity Function and Galaxy Evolution of Abell 2256
	* Advisor: Dr.Lawrence Rudnick


* B.S. Physics, June 2010 -->

### Main Projects

#### Frequency-Domain Smoke Guiding

Art-directing smoke for special effects purposes is challenging. Scaling up the resolution can result in unpredictable changes in the behavior of the final animation due to the chaotic motion of fluid. We propose a simple and efficient method for guiding an Eulerian smoke simulation to match the behavior of a specified velocity field, such as a low-resolution animation of the same scene, while preserving the rich, turbulent details arising in the simulated fluid. Our method works by simply combining the high-frequency component of the simulated fluid velocity with the low-frequency component of the input guiding field.
<a href="fdsg.html">Project page</a>



#### Uncertainty Models for TTC-Based Collision Avoidance

In this work, we tackle the problem of uncertainty in sensing data for multi-agent navigation and planning based on a collision avoidance model called Time-To-Collision (TTC). We propose two approaches that assume uncertainty in velocity of agents, isotropic and adversarial model. The isotopic model considers all possible uncertainties while the adversarial model has the uncertainty only in the direction of the head-on collision. We analyze our methods mathematically and experimentally to show that these models can produce collisionfree interaction between agents.
<a href="uttc.html">Project page</a>



#### The Radio Luminosity Function and Galaxy Evolution of Abell 2256 (Master Thesis)

For my master thesis in Astrophysics I worked on the Galaxy evolutions in the large scale structures. There are many observations in radio wavelength that shows diffuse and large emissions in the galaxy clusters called radio halo and relic. The origin of these emissions are still unknown but scientist believe that they probably created during mergings of galaxy clusters.
In my theses I looked at the cluster Abell 2256 that know as merging cluster and has a big radio halo. In my work I studied the effect of this merging subclusters on each galaxy in the cluster. I found very interesting results.
Find the link to my full thesis [here](https://conservancy.umn.edu/handle/11299/170735).



#### Small Projects

Quaternions: Walking Skeleton ([More information](./walking_skeleton.md))

Smoothed-particle hydrodynamics(SPH) : Accretion Disk ([More information](./sph.md))

Computer Vision Class project : Region detection

Computer Graphics Class project : Raytracer




[All codes](https://bitbucket.org/Zahrafn/)

[Resume](pdfs/resume.pdf)

<!-- Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl> 

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
-->
