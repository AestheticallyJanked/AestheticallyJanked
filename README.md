/**
 * @name Neumorphism
 * @author Gryzle
 * @description Give Discord a new, soft look via Neumorphism. This is a theme in the form of a plugin to provide easy customization for the end user.
 * @version ersion Release 1.0.1
 * @authorId 468465766786793482
 * @authorLink https://github.com/Gryzle
 * @source https://github.com/Gryzle/Neumorphism
 * @website https://github.com/Gryzle/Neumorphism
 * @updateUrl https://github.com/Gryzle/Neumorphism/releases
 */

@import url(https://raw.githack.com/Gryzle/Neumorphism/main/CSS/MacOSPatch.css);

:root {

	/*Default Theme (Light): 
	--theme: #e0e0e0;

	--highlight: #ffffff;
	--highlight-alt: #f0f0f0;
	--highlight-alt-2: #f6f6f6;
	--shadow: #bebebe;
	--shadow-alt: #cacaca;
	--text-color: #000;
	--text-accent: #303030;
	--text-accent-alt: #505050;

	/*Blue Theme: 
	
	--theme: #394260;

	--highlight: #424c6e;
	--highlight-alt: #3d4767;
	--highlight-alt-2: #424c6e;
	--shadow: #303852;
	--shadow-alt: #333b56;
	--text-color: #fff;
	--text-accent: #f5f5f5;
	--text-accent-alt: rgb(220,220,220);

	/*Dark Theme:  */

	--theme: #1e1f22;

	--highlight: #1a1a1d;
	--highlight-alt: #2f3237;
	--highlight-alt-2: #1a1a1d;
	--shadow: #25282b;
	--shadow-alt: #282a2e;
	--text-color: #fff;
	--text-accent: #f5f5f5;
	--text-accent-alt: rgb(220,220,220);
/*
	--theme: #e0e0e0;

	--highlight: #ffffff;
	--highlight-alt: #f0f0f0;
	--highlight-alt-2: #f6f6f6;
	--shadow: #bebebe;
	--shadow-alt: #cacaca;

	/* COLORS - DISCORD */
	--text-normal: var(--text-color);
	--background-primary: var(--theme);
	--background-secondary: var(--theme);
	--background-tertiary: var(--theme);
	--background-secondary-alt: var(--theme);
	--header-primary: var(--text-accent);
	--header-secondary: var(--text-accent-alt);
	--brand-experiment-200: var(--text-accent);
	--background-floating: var(--theme);
	--interactive-active: var(--text-accent);
	--interactive-normal: var(--text-accent-alt);
	--interactive-hover: var(--text-accent-alt);

	--background-message-hover: rgba(0,0,0,0);
	--background-modifier-hover: rgba(0,0,0,0);
	--background-modifier-selected: rgba(0,0,0,0);

	--neumorphic-raised-3D: linear-gradient(145deg, var(--highlight-alt), var(--shadow-alt));
	--neumorphic-sinked-3D: linear-gradient(145deg, var(--shadow-alt), var(--highlight-alt));

	/* COLORS - CUSTOM */
	--new-blurple: #5865F2;
	--perfect-text: #303030;

	/* SHADOWS */
	--elevation-low: 0px 0px 1px 0px var(--header-secondary);

	--neumorphic-raised-flat: 5px 5px 10px var(--shadow), -5px -5px 10px var(--highlight);
	--neumorphic-sinked-flat: inset 2px 2px 5px var(--shadow-alt), inset -2px -2px 5px var(--highlight-alt-2);

	--neumorphic-raised-slight: 2px 2px 5px var(--shadow), -2px -2px 5px var(--highlight);
}

/* Channels */

.scroller-2LSbBU::-webkit-scrollbar, .contentRegionScroller-26nc1e::-webkit-scrollbar, .scrollerBase-289Jih::-webkit-scrollbar {
  display: none;
}

.selected-3LIHYU {
	border-radius: 50px;
	background: var(--neumorphic-sinked-3D) !important;
	box-shadow:  var(--neumorphic-raised-flat);
	margin-left: 5px;
	margin-right: 15px;
	transition: all 0.5s;
}

.selected-3LIHYU > div > div, .containerDefault--pIXnN > div > div, .content-1x5b-n {
	background-color: rgba(0,0,0,0) !important;
}

.containerDefault--pIXnN {
	border-radius: 20px;
	margin-left: 10px;
	margin-right: 15px;
	transition: all 0.5s;
	margin-bottom: 5px;
}

.containerDefault--pIXnN:hover {
	background: var(--neumorphic-raised-3D);
	box-shadow:  var(--neumorphic-raised-flat);
	transition: all 0.25s;
}

.name-23GUGE {
	color: var(--channels-default) !important;
}

/* Text/Message Box */

.scrollableContainer-2NUZem {
	border-radius: 15px;
	background: var(--theme);
	box-shadow: var(--neumorphic-sinked-flat);
}

.cooldownWrapper-3joyFc {
	color: var(--header-secondary) !important;
	opacity: 0.7;
}

.autocomplete-1vrmpx, .categoryHeader-O1zU94 {
	background-color: var(--theme) !important;
}

.selected-1Tbx07 {
	background-color: var(--theme) !important;
	box-shadow: var(--neumorphic-raised-slight);
}

.option-1B5ZV8 {
	background-color: var(--interactive-hover) !important;
}

/* Server List */

.wrapper-25eVIn {
	border-radius: 50px;
	background: var(--neumorphic-raised-3D);
	box-shadow:  var(--neumorphic-raised-slight);
}

.wrapper-1BJsBx.selected-bZ3Lue .childWrapper-anI2G9, .wrapper-1BJsBx:hover .childWrapper-anI2G9 {
	background-color: rgba(0,0,0,0);
}

/* Embed */

.container-1ov-mD > .embedWrapper-lXpS4L, .embedWrapper-lXpS3L {
	border-radius: 15px;
	background: var(--theme);
	box-shadow:  var(--neumorphic-raised-flat);
	border-color: rgba(0,0,0,0) !important;
	margin-top: 10px;
	margin-bottom: 10px;
}

.container-2xsjOj > .children-2goeSq > .button-38aScr {
	box-shadow: var(--neumorphic-raised-slight) !important;
	margin: 7px;
	margin-top: 6px;
}

/* Mentioned */

.mentioned-xhSam7 {
	border-radius: 15px;
	border: 1.5px solid var(--background-mentioned) !important;
	border-color: var(--info-warning-foreground) !important;
	/*
	background: var(--theme);
	box-shadow:  var(--neumorphic-raised-flat);
	margin: 10px;*/
}

.mentioned-xhSam7:before {
	background-color: rgba(0,0,0,0);
}

.repliedMessage-VokQwo {
	color: var(--text-accent);
}

.repliedMessage-VokQwo:before {
	opacity: 0.5;
}

/* Reactions */

.reactionCount-2mvXRV {
	color: var(--text-accent) !important;
}

.reaction-1hd86g.reactionMe-wv5HKu {
	border-color: rgba(0,0,0,0);
	/*background-color: var(--brand-experiment);*/
}

/* Window Header */

.wordmark-2iDDfm {
	/*background-image: url("https://fontmeme.com/images/discord-new-logo.png");
	background-size: cover;*/
	color: rgba(0,0,0,0);
}

.winButton-iRh8-Z {
	margin-top: 0px;
	height: 50px;
	color: var(--text-accent);
}

.app-1q1i1E {
	margin-top: -20px;
}

.toolbar-1t6TWx {
	margin-right: 80px;
}

.clickable-3rdHwn .icon-22AiRD {
	color: var(--text-accent-alt) !important;
	padding: 2px;
	border-radius: 5px;
}

.clickable-3rdHwn .icon-22AiRD:hover {
	background: var(--neumorphic-raised-3D);
	box-shadow:  var(--neumorphic-sinked-flat);
	transition: all 0.25s;
}

/* Profile Small */

.profileBanner-33-uE1 {
	opacity: 0.5;
}

.note-3HfJZ5 > .input-cIJ7To {
	background: var(--background-primary) !important;
	box-shadow: none !important;
}

/* Custom Status */

.theme-dark .footer-2gL1pp {
	background-color: var(--background-floating);
}

.input-cIJ7To {
	border-radius: 15px;
	background: var(--theme);
	box-shadow: var(--neumorphic-sinked-flat);
	border: none;
}

.select-2fjwPw {
	border-radius: 50px;
	background: var(--neumorphic-raised-3D);
	box-shadow:  var(--neumorphic-raised-flat);
	border: none;
}

.popout-VcNcHB {
	border-radius: 15px;
	margin-top: 5px;
	box-shadow: 0px 10px 30px 0px rgba(0,0,0,0.5);
}

.modalRoot-1Kx4Hb > .footer-2gL1pp > .colorBrand-3pXr91 {
	border-radius: 25px;
	background: var(--neumorphic-raised-3D);
	box-shadow:  var(--neumorphic-raised-flat);
	border: none;
}



/* UNIVERSAL BUTTON */
.lookFilled-1Gx00P {
	border-radius: 25px;
	background: var(--neumorphic-raised-3D);
	box-shadow:  var(--neumorphic-raised-flat);
	border: none;
	color: var(--text-accent-alt) !important;
}



.modalRoot-1Kx4Hb > .footer-2gL1pp > .colorBrand-3pXr91 > .contents-18-Yxp {
	color: var(--brand-experiment);
}

/* Settings */

.radioBar-bMNUI- {
	background-color: var(--radio-bar-accent-color);
	filter: brightness(1.2);
}

.radioIconForeground-XwlXQN {
	color: var(--new-blurple);
}

.avatarUploaderInner-3UNxY3 {
	background-color: rgba(0,0,0,0);
}

.background-1QDuV2 {
	border-radius: 15px;
	background: var(--theme);
	box-shadow:  var(--neumorphic-raised-flat);
}

.closeButton-1tv5uR > svg > path {
	fill: #72767D;
}

.homeIcon-FuNwkv {
	margin-left: -2px;
	margin-top: 1px;
	border-radius: 5px;
}

.homeIcon-FuNwkv > path {
	fill: var(--text-accent);
	d: path("M 10.191406 0.3125 C 9.222656 0.523438 8.121094 0.867188 6.980469 1.3125 L 5.878906 1.746094 L 5.488281 2.351562 C 2.863281 6.464844 1.628906 11.191406 1.972656 15.804688 L 2.035156 16.632812 L 2.976562 17.257812 C 3.980469 17.925781 5.472656 18.734375 6.503906 19.167969 C 7.046875 19.398438 8.53125 19.933594 8.617188 19.933594 C 8.742188 19.933594 10.097656 17.644531 10.011719 17.578125 C 9.992188 17.558594 9.511719 17.324219 8.949219 17.054688 L 7.921875 16.5625 L 8.289062 16.195312 L 9.21875 16.554688 C 12.964844 17.992188 16.804688 17.996094 20.488281 16.554688 L 21.367188 16.210938 L 21.8125 16.5625 L 20.910156 16.996094 C 20.417969 17.238281 19.972656 17.433594 19.925781 17.433594 C 19.527344 17.433594 19.707031 17.910156 20.625 19.289062 C 21.082031 19.976562 21.023438 19.960938 21.976562 19.625 C 24.507812 18.742188 27.578125 16.984375 27.695312 16.351562 C 27.824219 15.652344 27.675781 11.640625 27.476562 10.527344 C 26.816406 6.8125 24.660156 2.164062 23.3125 1.550781 C 22.0625 0.980469 19.296875 0.171875 18.605469 0.171875 C 18.429688 0.171875 18.34375 0.28125 18.074219 0.824219 L 17.753906 1.480469 L 17.046875 1.40625 C 16.128906 1.316406 13.523438 1.316406 12.640625 1.410156 L 11.953125 1.480469 L 11.632812 0.828125 C 11.265625 0.0820312 11.257812 0.078125 10.191406 0.3125 M 11.535156 8.703125 C 13.203125 9.554688 13.246094 12.289062 11.609375 13.25 C 10.527344 13.886719 9.234375 13.429688 8.625 12.191406 C 7.589844 10.082031 9.578125 7.699219 11.535156 8.703125 M 20.03125 8.675781 C 22.257812 9.742188 21.554688 13.503906 19.132812 13.5 C 16.507812 13.496094 16.078125 9.363281 18.617188 8.535156 C 18.949219 8.425781 19.65625 8.496094 20.03125 8.675781 M 0.324219 0 L 1.613281 0 L 1.613281 1.292969 L 0.324219 1.292969 Z M 28.054688 0 L 29.34375 0 L 29.34375 1.292969 L 28.054688 1.292969 Z M 28.054688 0 ") !important;
}

.cardPrimaryEditable-3KtE4g {
	background-color: var(--background-primary);
}

.previewOverlay-2O7_KC {
	background-color: var(--theme) !important;
}

.lookOutlined-3sRXeN.colorRed-1TFJan {
	box-shadow: var(--neumorphic-sinked-flat);
	border-radius: 15px;
}

.side-8zPYf6 > .item-PXvHYJ {
	background-color: rgba(0,0,0,0) !important;
}

.side-8zPYf6 > .selected-3s45Ha {
	box-shadow: var(--neumorphic-raised-flat);
	background: var(--neumorphic-sinked-3D) !important;
}

.side-8zPYf6 > .item-PXvHYJ {
	background-color: rgba(0,0,0,0) !important;
	border-radius: 15px !important;
	transition: all 0.5s;
	margin-right: 15px;
}

.side-8zPYf6 > .item-PXvHYJ:hover {
	box-shadow: var(--neumorphic-raised-flat);
	background: var(--neumorphic-raised-3D);
}

/* Settings Slider */

.container-3auIfb {
	background-color: #85ED91;
	filter: brightness(1.2);
}

/* Settings TOS */

.cardPrimary-1Hv-to {
	padding: 0px;
	background-color: rgba(0,0,0,0);
}

/* OTHER */

.theme-dark .root-1gCeng {
	background-color: var(--theme);
}

.icon-3D60ES {
	color: #9B9B9B;
}

.container-CpszHS {
	border-radius: 15px;
	background: var(--theme) !important;
	box-shadow: var(--neumorphic-sinked-flat);
	border: none;
}

/* HOME PAGE */

.theme-dark .container-1D34oG {
	background-color: var(--background-primary);
}

.searchFilter-2ESiM3, .searchAnswer-3Dz2-q {
	background-color: var(--text-accent) !important;
}

/* TEXT FIELDS THAT NEED EXTRA */
.wrapper-1cBijl, .css-gvi9bl-control {
	border-radius: 15px;
	background: var(--theme);
	box-shadow: var(--neumorphic-sinked-flat);
	border: none;
}

.css-gvi9bl-control > div > div {
	color: var(--text-accent);
}

/*
.message-2qnXI6.selected-2P5D_Z, .mouse-mode.full-motion .message-2qnXI6:hover {
	background-color()
}*/


/* EMOJIS */
.emojiItem-14v6tW.emojiItemSelected-1aLkfV {
	background-color: rgba(255,255,255,0.5);
}

.emojiItemDisabled-1FvFuF {
	opacity: 0.25;
	/*
	background-image: url("https://www.freeiconspng.com/thumbs/lock-icon/lock-icon-11.png");
	background-size: cover;*/
}

.header-1TOWci {
	box-shadow: var(--elevation-low) !important;
}

/* DISCOVER */

.theme-dark .pageWrapper-1PgVDX {
	background-color: var(--background-primary);
}

.searchBox-3Y2Vi7 {
	border-radius: 15px;
	background: var(--theme) !important;
	box-shadow: var(--neumorphic-sinked-flat), 0 2px 5px 0 rgba(0,0,0,.2) !important;
}

.searchBox-3Y2Vi7 > .inputWrapper-31_8H8 > .input-cIJ7To {
	border-radius: 15px;
	background: transparent;
	box-shadow: none !important;
	border: none !important;
}

.container-1CE3eW > div > div {
	transform: none !important;
	top: 0 !important;
}

/* Unread Channel Indicator */

.unread-2lAfLh {
	border: 2px solid var(--header-secondary);
	width: 0px;
	height: 4px;
	margin-bottom: 2px;
}

/* Image Import */

.uploadModal-2ifh8j {
	background-color: var(--background-primary) !important;
}

.footer-3mqk7D {
	background-color: var(--background-secondary) !important;
	box-shadow: none !important;
}

.lookLink-9FtZy-.colorPrimary-3b3xI6 {
	color: var(--text-accent-alt) !important;
}

/* Stream / VC View */

.streamPreview-3YL8OQ > .lookFilled-1Gx00P {
	box-shadow: none !important;
}

.content-2Sfaij > div {
	background-color: rgba(50,50,50,0.25) !important;
}

/* Context Menu */

.menu-3sdvDG > div {
	margin-right: 8px;
}

/* Server Boost Screen */

.perksModal-fSYqOq, .tierBody-16Chc9, .tierHeaderLocked-1s2JJz {
	background-color: var(--theme) !important;
}

.carouselItemSelected-JFUsnG > div {
	box-shadow: var(--neumorphic-raised-flat) !important;
	border-radius: 15px !important;
}

.tierWrapper-W9ajqp {
	box-shadow: none !important;
	transform: none !important;
	border-radius: 15px !important;
}

.item-287JPa {
	box-shadow: var(--neumorphic-sinked-flat) !important;
	border-radius: 15px !important;
}

.tierHeader---JJFb {
	border-radius: 15px 15px 0 0;
}

.tierBody-16Chc9 {
	border-radius: 0 0 15px 15px;
}

.perk-2WeBWW {
	background-color: rgba(0,0,0,0) !important;
}

.avatar-3uk_u9 > div > svg > foreignObject {
	mask: none;
	border-radius: 50%;
}

.avatar-3uk_u9 > div > svg > rect {
	x: 27;
}

/* Friends / Home */

.nowPlayingColumn-2sl4cE > .container-lRFx4q > div > div {
	box-shadow: var(--neumorphic-raised-flat);
	background-color: var(--theme) !important;
	border-radius: 15px;
	margin-bottom: 15px;
}

.nowPlayingColumn-2sl4cE > .container-lRFx4q > div > div > div > .body-1ld4H7 {
	box-shadow: var(--neumorphic-raised-flat);
	background-color: var(--theme) !important;
}

.selected-aXhQR6 {
	box-shadow: var(--neumorphic-raised-flat);
	background: var(--neumorphic-sinked-3D) !important;
}

.channel-2QD9_O {
	background-color: rgba(0,0,0,0) !important;
	border-radius: 15px;
	transition: all 0.5s;
	margin-right: 15px;
	margin-left: 15px;
}

.channel-2QD9_O:hover {
	box-shadow: var(--neumorphic-raised-flat);
	background: var(--neumorphic-raised-3D);
}

.clickable-1JJAn8:active .layout-2DM8Md {
	background-color: rgba(0,0,0,0) !important;
}
