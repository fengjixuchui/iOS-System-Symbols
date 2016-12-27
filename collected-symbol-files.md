##Symbols list

There are 49 versions from `7.0 (11A465)` to `10.2 (14C92)`. I got 39 of them.

Here is the list of symbols from `7.0`to`10.2`, with their CPU architecture version I've got.

I will update the list if i get new symbol files.

			  OS Version				|	Collected CPU Version
---------------------------------	|------------------------
10.2 (14C92)							|arm64,armv7s
10.1.1 (14B150)						|arm64,armv7s
10.1.1 (14B100)						|arm64,armv7s
10.1 (14B72c)							|arm64,armv7s
10.1 (14B72)							|arm64,armv7s
10.0.3 (14A551)						|arm64,armv7s
10.0.2 (14A456)						|arm64,armv7s
10.0.1 (14A403)						|arm64,armv7s
**10.0(14A346)iPhone 7和7s独占**	|**none**
9.3.5 (13G36)							|arm64,armv7s,armv7
9.3.4 (13G35)							|arm64,armv7s
9.3.3 (13G34)							|arm64,armv7s,armv7
**9.3.2(13F72)iPad Pro 9.7寸独占**	|**none**
9.3.2 (13F69)							|arm64,armv7s,armv7
9.3.1 (13E238)						|arm64,armv7s,armv7
**9.3(13E237)5s及以下机型独占**		|**none**
**9.3(13E236)iPad2独占**			|**none**
**9.3(13E234)6s独占**				|**none**
9.3 (13E233)							|arm64,armv7s
9.2.1 (13D20)							|arm64,armv7s
9.2.1 (13D15)							|arm64,armv7s,armv7
9.2 (13C75)							|arm64,armv7s,armv7
9.1 (13B143)							|arm64,armv7s,armv7
9.0.2(13A452)							|arm64,armv7s
9.0.1(13A404)							|arm64,armv7s
9.0 (13A344)							|arm64,armv7s,armv7
8.4.1 (12H321)						|arm64,armv7s,armv7
8.4 (12H143)							|arm64,armv7s,armv7
8.3 (12F70) iPhone独占				|arm64,armv7s
8.3 (12F69) iPad独占					|arm64,armv7s,armv7
8.2 (12D508)							|arm64,armv7s
8.1.3 (12B466)						|arm64,armv7s
8.1.2 (12B440)						|arm64,armv7s,armv7
8.1.1 (12B436)iPhone6以上独占		|arm64,armv7s
8.1.1 (12B435)						|armv7s
**8.1 (12B411) iPhone独占**			|**none**
8.1 (12B410) iPad独占				|arm64,armv7s
8.0.2 (12A405)						|arm64,armv7s,armv7
**8.0.1(12A402)**					|**none**
8.0 (12A366)							|arm64,armv7s
7.1.2 (11D257)						|armv7
7.1.1 (11D201)						|arm64,armv7s,armv7
7.1 (11D167)							|arm64,armv7s,armv7
7.0.6 (11B651)						|arm64,armv7s
7.0.4 (11B554a)						|arm64,armv7s
7.0.3 (11B511)						|arm64,armv7s
**7.0.2(11A501)**					|**none**
**7.0.1(11A470a)**					|**none**
**7.0(11A465)**						|**none**

##Missing Symbols

	Missing OS	|Missing CPU version|	description
----------------	|-------------------|----------------
10.0(14A346)		|arm64					|iPhone 7 and 7s-only, default OS when leave factory
9.3.4 (13G35)		|armv7					|
9.3.2(13F72)		|arm64					|iPad Pro 9.7-inch-only, fix bricked problem
9.3(13E237)		|arm64,armv7s,armv7	|5s and older device only, fix activation problem
9.3(13E236)		|armv7					|iPad2-only, fix activation problem
9.3(13E234)		|arm64					|6s-only
9.3(13E233)		|armv7					|
9.0.2(13A452)		|armv7					|
9.0.1(13A404)		|armv7					|
8.3 (12F70)		|armv7					|iPad-only
8.1.3 (12B466)	|armv7					|
8.1.1 (12B435)	|arm64,armv7			|
8.1 (12B411) 		|arm64,armv7s,armv7	|iPhone-only
8.1 (12B410)		|armv7					|
8.0.1(12A402)		|arm64,armv7s,armv7	|`8.0.1`was pulled soon after released.Because it has serious bugs
8.0 (12A366)		|armv7					|
7.1.2 (11D257)	|arm64,armv7s			|
7.0.6 (11B651)	|armv7					|
7.0.4 (11B554a)	|armv7					|
7.0.3 (11B511)	|armv7					|
7.0.2(11A501)		|arm64,armv7s,armv7	|
7.0.1(11A470a)	|arm64,armv7s,armv7	|
7.0(11A465)		|arm64,armv7s,armv7	|

## CPU Architecture with Devices

  CPU	|	Devices
------	| ------
armv6	| iPhone, iPhone2, iPhone3G, iPod Touch 1 and 2
armv7	| iPhone3GS, iPhone4, iPhone4S，iPad, iPad2, iPad3(The New iPad), iPad mini，iPod Touch 3G, iPod Touch4
armv7s	| iPhone5, iPhone5C, iPad4(iPad with Retina Display)
arm64	| iPhone5S, iPad Air, iPad mini2(iPad mini with Retina Display), iPhone6, iPhone6s, iPhone7, iPhone7s and any new device in the future