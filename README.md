# responsive
_responsive_ is my answer to feeling creatively restricted by bootstrap. Often I find myself including all of bootstrap in a project when really all that I want is the ability to create a responsive design easily. Bootstrap does this wonderfully but also comes with a lot of other weight and styles that encourage me to design my sites a certain way.

## How to use responsive
_responsive_ is a collection of containers used to help align websites - and thats all it does.

### Containers
**.container-extended** is a full-width container taking up 100% of the screen

**.container** is a responsive container. `.container` takes up 96% of the screen on phones and 80% of the screen on all other devices

### Row
**.row** is essentially a container but is more semantic

### Columns
There are 4 types of columns: _phone_, _tablet_, _desktop_, and _wide_. Each have specific widths ranging from 10-100% of the parent width.
The class names follow the style `.[device]-col-[size]` where device is phone, tablet, desktop or wide, and size is 1-10 representing 10-100% of width.
