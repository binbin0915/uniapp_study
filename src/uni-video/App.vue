<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
			uni.hideTabBar({
				
			})
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	html,body{
		width: 100%;
		height: 100%;
	}
	uni-page-body{
		height: 100%;
	}
	@font-face {font-family: "iconfont";
	  src:url('data:application/x-font-woff2;charset=utf-8;base64,d09GMgABAAAAAAOIAAsAAAAAB3QAAAM6AAEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAHEIGVgCDHAqCOIInATYCJAMQCwoABCAFhG0HPhuPBsiemjxpBMVoZAykf/CmrwFDPPw39u2+mVkRTaJJkxiQzST9Ct60BULhEArdJLT9aT/3EPND07yxhFmaOXK3+X3FPYpVs0SmeiZBaKbzf64ftrUNB9IgA4ykvZnGgUSEwFGWHu0d0OmHiZxmgXIm3//ncnq1Bee3s1zWXHQ9HxMwsDSwsQdZgSToDdNLHIhLmwnUGyYRtm1Hhw5iFV6vQFy95O6E2JpfUViqVqjumVjEa1ClNj1BnwDwKv1+/AJm1JJUZd7Anecbe6DmK1XauEIqjsYIEOxnBZtGxgxQiIu99tMi8viMCPWmeaRFoFatxF51cmkTgozcmOf/5RGSTFTzsI1gHiUyX6kQJfgqoyS+2hgZPoih1hMlDwMVTBp8TJJET1piY/+QIfvyE7/fhudT93rpKw9WuLq7PdF1Vbw96sSHuvSSjA88ySruLyaOqlp3puOH7uh3s6Xjgpr388UD/+pm5t6kZzOoVDMb91UW71wZZu8PO/Bmqfpm6tkaXimPoD5/uFy2Iy/+fIlINOczXHz7Y9n/1+d66wln18dYuV4vZ8fkjN5Q0MYYucHAkW1Zgx7G9kLqg4q+1NhLDiGoPAwuARfhRtSl58ufamn8v/lnVZeeXXDW7o75u+2mhAHY+uYuHk67v/ICTwOQ19LJ//IbD78nv5Rf+qahgC+Najr0b70KmM9/uQIj+AuCmWXFijxDKVoc8h1nMbG6R0K9erz7NO2e9lB2zY4SamsCBkmNIchqjeAKaQaqNJiHarVWod605ukNOnAiRKnDlBkAodU5JM0+QtbqHldIj1Cl2zNUa40M9fZHx4INxuJS/eZt3CngHtQ1gLzdNEQCkxCfZWqwWwx0clVRSjNgjveGkFKmaKaacQhzewzhe90qQSCIcDSImsB2OBCgiOGoD3cLMo8gMGq5nPS9SdZNgxBvEwfrJMB6IF0GIF7dqBAS1xbEtz6vgbmJAjpxI1kNuwHG4XkbR5RkFDNwzfLQrKx3uYbXy01FICAQgkMFIU3AigX8OIUw/e18sG4CGc+KKENNjqqRuXLZ+crgC+SxPLzTSqTIUaJK9Z0bIi/S8Fll9PlTIY/oBQAAAA==')
	}
	
	.iconfont {
	  font-family: "iconfont" !important;
	  font-size: 16px;
	  font-style: normal;
	  -webkit-font-smoothing: antialiased;
	  -moz-osx-font-smoothing: grayscale;
	}
	
	.icon-sousuo:before {
	  content: "\e60a";
	}
	
	.icon-21:before {
	  content: "\e620";
	}
	
	.icon-fanhui:before {
	  content: "\e64f";
	}
	

</style>
