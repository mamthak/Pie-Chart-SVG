svg {
  width: 100px;
  border-radius: 50%;
  background:yellowgreen; 
  transform: rotate(-90deg);
}
 
circle {
  fill: none;
  stroke-width: 32;
  r: 16;
  cx: 16;
  cy: 16;
}
 
circle.first {
  stroke: deeppink;
}
 
circle.second {
  stroke: #fb3;
}
  
circle.third {
  stroke: black;
}


<svg viewBox="0 0 32 32">
  <circle class='first' stroke-dasharray="75 100"></circle>
  <circle class='second' stroke-dasharray="50 100"></circle>
  <circle class='third' stroke-dasharray="24 100"></circle>
</svg>
