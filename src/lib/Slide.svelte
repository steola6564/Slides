<script lang="ts">
	// Color Backgrounds
	export let bgColor: any = null;
	// Gradient Backgrounds
	export let bgGradient: any = null;
	// Image Backgrounds
	export let bgImage: any = null;
	export let bgSize: any = "cover";
	export let bgPosition: any = "center";
	export let bgRepeat: any = "no-repeat";
	export let bgOpacity: any = 1.0;
	// Video Backgrounds
	export let bgVideo: any = null;
	export let bgVideoLoop: any = false;
	export let bgVideoMuted: any = true;
	// Iframe Backgrounds
	export let bgIframe: any = null;
	export let bgInteractive: any = false;
</script>

<section
		data-background-color={bgColor}
		data-background-gradient={bgGradient}
		data-background-image={bgImage}
		data-background-size={bgSize}
		data-background-position={bgPosition}
		data-background-repeat={bgRepeat}
		data-background-opacity={bgOpacity}
		data-background-video={bgVideo}
		data-background-video-loop={bgVideoLoop}
		data-background-video-muted={bgVideoMuted}
		data-background-iframe={bgIframe}
		data-background-interactive={bgInteractive}
>
		<slot/>
</section>
