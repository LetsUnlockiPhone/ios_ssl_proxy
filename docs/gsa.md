# Research on gsa.apple.com:

## For the initial post to https://gsa.apple.com/grandslam/GsService2 with a plist xml formatted body:

### This initial body seems to be what sets up many of the header fields used later, such as X-Apple-I-MD, X-Apple-I-MD-M, etc. Below is the initial packet:

	POST https://gsa.apple.com/grandslam/GsService2
	Content-Type: text/x-xml-plist^M
	Accept: */*^M
	Accept-Language: en-us^M
	User-Agent: akd/1.0 CFNetwork/808.2.16 Darwin/16.3.0^M
	X-MMe-Client-Info: <iPhone8,2> <iPhone OS;10.2;14C92> <com.apple.akd/1.0 (com.apple.akd/1.0)>^M
	Content-length: 2168^M
	Host: gsa.apple.com^M
	Accept-Encoding: gzip, deflate^M
	<?xml version="1.0" encoding="UTF-8"?>
	<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
	<plist version="1.0">
	<dict>
			<key>Header</key>
			<dict>
					<key>Version</key>
					<string>1.0.1</string>
			</dict>
			<key>Request</key>
			<dict>
					<key>app</key>
					<array>
							<string>com.apple.gs.appleid.auth</string>
					</array>
					<key>c</key>
					<data>
					NTBmNjljMmItZWJlMS00MDAyLTgwYmMtMWU2YWQzMjQ1MDRiQUh2Mk1RdnNi
					LzdJNUdBT0dJbXF6b0tUN0huVWJuMjZPek9RWlJDczFnM2RTNUJZSzEvM0Fz
					UWFROGRoaTVRcXRjd1N4OUhyRGlDdHk3T2NXRHVQOUw0anZlNEdlaU5ZQUE4
					d3FYUDJpZDdPVGlVeXYwVm9QME1DZWJFejlwaldXRnBI
					</data>
					<key>checksum</key>
					<data>
					dIfTy0pydCA/s1ijzF7256VGrismz98/N4gsPdf2uJ8=
					</data>
					<key>cpd</key>
					<dict>
							<key>AppleIDClientIdentifier</key>
							<string>36ADD28C-3BE0-4E36-96A3-B5CF27677963</string>
							<key>X-Apple-I-Client-Time</key>
							<string>2017-02-01T22:59:19Z</string>
							<key>X-Apple-I-MD</key>
							<string>AAAABQAAABAP8dw5sHseHxVwLdi116YZAAAAAw==</string>
							<key>X-Apple-I-MD-M</key>
							<string>7uFG2/ZgB6SmF5r93yaqedoq+rugYFfglwmtO8rZlzO2ICtyDYMjk28WsJ7Ao7BMiPcwfupM8nF8zW87</string>
							<key>X-Apple-I-MD-RINFO</key>
							<string>17106176</string>
							<key>X-Apple-I-SRL-NO</key>
							<string>F2LS47Z9HFM2</string>
							<key>X-Mme-Device-Id</key>
							<string>87cda23a7230769ef6aa1ded8a99a5d3e65b9d42</string>
							<key>capp</key>
							<string>accountsd</string>
							<key>dc</key>
							<string>#b9b7ba</string>
							<key>dec</key>
							<string>#272728</string>
							<key>loc</key>
							<string>en_US</string>
							<key>papp</key>
							<string>Preferences</string>
							<key>pbe</key>
							<false/>
							<key>prtn</key>
							<string>MN3E2</string>
							<key>svct</key>
							<string>iCloud</string>
					</dict>
					<key>o</key>
					<string>apptokens</string>
					<key>t</key>
					<string>AAAABLwIAAAAAFiSMJ4RDGdzLmlkbXMuYXV0aL0ATq91nbHk0WNNFpN1hvqHyF6Jbx/q+sIVamHTN50CGOX4gBAaljQMu7iP4O93xsavh+D0+OL8NX/7XN7j3iJFxIxkO+9KvRxBFhVjYQeK+OpRwI3BU14+ddrUpmPiIo4NEk1hLInsfTaVT3NxLiIYjNhTYcqhfNPsNKY684CUYnItNJiQ+rM9jRovG49nZiITauJnWB0ftvNWWXUgMLXv9yw9oCU=</string>
					<key>u</key>
					<string>000919-05-b45534a8-fa23-4dfa-9ff7-0fcfa37c3d34</string>
			</dict>
	</dict>
	</plist>




