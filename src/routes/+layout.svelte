<script>
    import "../app.css"
//   import { browser } from '$app/environment';
//     import * as handTrack from 'handtrackjs';
//   import { onMount } from 'svelte';

//     let canvas;
//     let ctx
//   let videoSource = null;
//   let loading = false;
//   const defaultParams = {
//     flipHorizontal: false,
//     outputStride: 16,
//     imageScaleFactor: 1,
//     maxNumBoxes: 20,
//     iouThreshold: 0.2,
//     scoreThreshold: 0.6,
//     modelType: "ssd640fpnlite",
//     modelSize: "large",
//     bboxLineWidth: "2",
//     fontSize: 17,
// };

// const model = async ()=>await handTrack.load(defaultParams)
// const mod = model()
//   const obtenerVideoCamara = async () => {
//     try {
//       loading = true;
//       const stream = await navigator.mediaDevices.getUserMedia({
//         video: true,
//       });
//       videoSource.srcObject = stream;
//       videoSource.play()
//       loading = false;
      
      
//     } catch (error) {
//       console.log(error);
//     }
//   };
//   function handleCanvas(src){
//     setInterval(() => {
//         captureFrame()
//     }, 1);
//   }
//    const captureFrame = async () => {
//         if (videoSource && canvas) {
//             ctx.drawImage(videoSource, 0, 0, canvas.width, canvas.height);
//             const imageData = canvas.toDataURL('image/png');
//             console.log(await (await mod).detect(canvas))
//             // console.log('Captured frame as image:', imageData);
//         }
//     };
//   if(browser){
//     obtenerVideoCamara()


//   }
//  onMount(() => {
// 		ctx = canvas.getContext('2d')
// 		ctx.width = 400
//         ctx.height = 400
// 	})
</script>
<slot />