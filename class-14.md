# CSS Transforms, Transitions and Animation 

## Transform
Transforms is a new way to postion and alter elements. The transform property comes in two different settings, two-dementional and three-deimensional that come with their own properities and values. 

- Transform Syntax: 
`div {
  webkit - transform:scale(1.5);
  more-transform: scale(1.5);
  o - transform: scale (1.5);
  transform: scale (1.5);
}`

- 2d Transform - Two dimensional transforms work on the x and y axes (horizontal and vertical axes)

- 2d Rotate - Rotate value provides the ability to rotate and element from  0-360 degrees.

CSS: `box -1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}`

- 2D scale - Using Scale value within the transform property allows you to change the appeared size of an element. 

## Transitions 

CSS3 allows you to alter the apperance and behavior of an element whenver a state change occcurs, like a hover over, focused on, active or targeted. 

Example code: 

` .box {
  transition: property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}`