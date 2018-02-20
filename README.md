### 360




<script src="//360.vizor.io/scripts/embed.js" data-vizorurl="https://360.vizor.io/embed/v/dak1r" ></script>



<script src="https://storage.googleapis.com/vrview/2.0/build/vrview.min.js"></script>

<div id='vrview'></div>

window.addEventListener('load', onVrViewLoad);

function onVrViewLoad() {
  // Selector '#vrview' finds element with id 'vrview'.
  var vrView = new VRView.Player('#vrview', {
    video: 'https://photos.app.goo.gl/TdsyfqmWlNjIdJZo1',
    is_stereo: true
  });
}


// Selector '#vrview' finds element with id 'vrview'.
var vrView = new VRView.Player('#vrview', {
  video: 'https://photos.app.goo.gl/Otu5loIL5VpNXjli1',
  is_stereo: true
});
