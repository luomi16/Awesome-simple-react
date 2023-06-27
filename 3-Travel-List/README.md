## Travel List Project - A very simple base react project

### Preview image

<img src="../images/travellist.png">

## The key knowledge points I use

### The method of passing data to sibling component:

lift up state: move the code of defining state to the closest common parent component

<img src="../images/Travelliststate.png">

### Chilf-to-Parent Communication

<img src="public/1.png">
<img src="public/2.png">
<img src="public/3.png">

The solution is to pass the set coupons function down as a prop to the components who need to update the state
parent ---setCoupons()---> child
