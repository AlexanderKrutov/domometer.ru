<div class="device-container device-container-help">
	<div class="device-mockup nexus6 portrait device-help">
		<div class="device">
			<div class="screen help">
				<video class="help" style="width:100%; height:100%" poster="/assets/img/screens/{{page.video}}.png">
					<source src="/assets/videos/{{page.video}}.mp4" type="video/mp4">Ваш браузер не поддерживает это видео.
				</video>
				<div class="playpause"></div>
			</div>
		</div>		
	</div>	
</div>

<script type="text/javascript">
	$(document).ready(function() {
		
		var video = $("video.help").get(0);
		
		$(".screen.help").click(function (e) {
			if (video.paused) {
				$(".playpause").fadeOut();
				video.play();
				$(".pause").fadeIn();
				//if (window.innerHeight > window.innerWidth) {
				//	fullScreenOn(video);
				//}
			} else {
				video.pause();
				$(".playpause").fadeIn();
				fullScreenOff(video);
			}
		});
		
		$(".screen.help").dblclick(function (e) {
			fullScreenOn(video);
		});
	
		video.addEventListener('ended', function() {		
			video.src = ''; 
			video.removeAttribute('src')
			$(".playpause").fadeIn();
			fullScreenOff(video);
		});
	});
	
	function fullScreenOff(video) {
		if (video.exitFullscreen) {
			video.exitFullscreen();
		} else if (video.mozExitFullScreen) {
			video.mozExitFullScreen();
		} else if (video.webkitExitFullscreen) {
			video.webkitExitFullscreen();
		}	
	}
	
	function fullScreenOn(video) {
		if (video.requestFullscreen) {
			video.requestFullscreen();
		} else if (video.mozRequestFullScreen) {
			video.mozRequestFullScreen();
		} else if (video.webkitRequestFullscreen) {
			video.webkitRequestFullscreen();
		}	
	}
	
</script>