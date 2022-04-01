# Release Rules

# \+ \[ REMUXES \] +

Remuxes are defined as any content that includes a video track that is released on the physical mediums of DVD, Bluray or UHD Bluray. Any content that does not meet the above requirements is not deemed a remux until a further revision is made and is not controlled by the below content.

Note: Remuxes are currently only defined for 2d content. If a desire to release a 3D remux arises, a discussion needs to be initiated around that format before doing so.

When releasing a remux, it is strongly urged to release both a “standard” and MULTi release. The source used to create the “standard” release will likely already include additional languages for a MULTi release at little additional effort. Similarly, the effort to create a “standard” from a MULTi is trivial in removing the unneeded tracks. There is no strict requirement to release any one type of version.

## \[ Video \]

### Global Tags

Global tags should be added for IMDB, TMDB and TheTVDB to allow for better media scraping by programs like Plex

<table class="c28"><tbody><tr class="c14"><td class="c52 c43" colspan="1" rowspan="1"><p class="c3"><span class="c45 c44 c36">Target Type</span></p></td><td class="c63 c43" colspan="1" rowspan="1"><p class="c3"><span class="c45 c44 c36">Tag</span></p></td><td class="c59 c43" colspan="1" rowspan="1"><p class="c3"><span class="c45 c44 c36">Description</span></p></td><td class="c43 c53" colspan="1" rowspan="1"><p class="c3"><span class="c45 c44 c36">Example</span></p></td></tr><tr class="c8"><td class="c52" colspan="1" rowspan="5"><p class="c3"><span class="c1">70</span></p></td><td class="c63" colspan="1" rowspan="1"><p class="c3"><span class="c1">IMDB</span></p></td><td class="c59" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is used to specify the IMDB Id for the file. If the file is a movie, this is the IMDB Id for the Movie. If the file is a TV Episode, the IMDB Id is for the Series. If there is no entry in IMDB, do not include the tag</span></p></td><td class="c53" colspan="1" rowspan="1"><p class="c3"><span class="c1">&lt;Simple&gt;</span></p><p class="c3"><span class="c1">&nbsp; &nbsp;&lt;Name&gt;IMDB&lt;/Name&gt;</span></p><p class="c3"><span class="c1">&nbsp; &nbsp;&lt;String&gt;tt0083866&lt;/String&gt;</span></p><p class="c3"><span class="c1">&lt;/Simple&gt;</span></p><p class="c3 c18"><span class="c1"></span></p></td></tr><tr class="c8"><td class="c63" colspan="1" rowspan="1"><p class="c3"><span class="c1">TMDB</span></p></td><td class="c59" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is used to specify the TMDB Id for the file. If the file is a movie, this is the TMDB Id for the Movie. If the file is a TV Episode, the TMDB Id is for the Series. If there is no entry in TMDB, do not include the tag</span></p></td><td class="c53" colspan="1" rowspan="1"><p class="c3"><span class="c1">&lt;Simple&gt;</span></p><p class="c3"><span class="c1">&nbsp; &nbsp;&lt;Name&gt;TMDB&lt;/Name&gt;</span></p><p class="c3"><span class="c1">&nbsp; &nbsp;&lt;String&gt;movie/601&lt;/String&gt;</span></p><p class="c3"><span class="c1">&lt;/Simple&gt;</span></p></td></tr><tr class="c8"><td class="c63" colspan="1" rowspan="1"><p class="c3"><span class="c1">TVDB</span></p></td><td class="c59" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is used to specify the TVDB Id for the file. If the file is a movie, this is the TVDB Id for the Movie. If the file is a TV Episode, the TVDB Id is for the Series. If there is no entry in TVDB, do not include the tag</span></p></td><td class="c53" colspan="1" rowspan="1"><p class="c3"><span class="c1">&lt;Simple&gt;</span></p><p class="c3"><span class="c1">&nbsp; &nbsp;&lt;Name&gt;TVDB&lt;/Name&gt;</span></p><p class="c3"><span class="c1">&nbsp; &nbsp;&lt;String&gt;movie/758&lt;/String&gt;</span></p><p class="c3"><span class="c1">&lt;/Simple&gt;</span></p></td></tr><tr class="c8"><td class="c63" colspan="1" rowspan="1"><p class="c3"><span class="c1">Remuxed By</span></p></td><td class="c59" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is only used when the file is a Remux. The value should be the Release Groups name - HYPERbyte</span></p></td><td class="c53" colspan="1" rowspan="1"><p class="c3"><span class="c1">&lt;Simple&gt;</span></p><p class="c3"><span class="c1">&nbsp; &nbsp;&lt;Name&gt;Remuxed by&lt;/Name&gt;</span></p><p class="c3"><span class="c1">&nbsp; &nbsp;&lt;String&gt;HYPERbyte&lt;/String&gt;</span></p><p class="c3"><span class="c1">&lt;/Simple&gt;</span></p></td></tr><tr class="c8"><td class="c63" colspan="1" rowspan="1"><p class="c3"><span class="c1">Encoded By</span></p></td><td class="c59" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is only used when the file is an Encode. The value should be the Release Groups name - HYPERbit</span></p></td><td class="c53" colspan="1" rowspan="1"><p class="c3"><span class="c1">&lt;Simple&gt;</span></p><p class="c3"><span class="c1">&nbsp; &nbsp;&lt;Name&gt;Encoded by&lt;/Name&gt;</span></p><p class="c3"><span class="c1">&nbsp; &nbsp;&lt;String&gt;HYPERbit&lt;/String&gt;</span></p><p class="c3"><span class="c1">&lt;/Simple&gt;</span></p></td></tr></tbody></table>

#### Guide

\[How to add Global tags; to be populated\]

### Angles

When multiple angles exist, the angle corresponding to the main audio track’s language should be used. For example, if the main Audio Track is in English, then the angle should also be the English angle. Only a single video track is accepted in the final file.

#### Guide

\[How to find the proper Angle to be populated

### Playlist Obfuscation

When Playlist obfuscation is present, the proper playlist should be selected

#### Guide

\[How to find the proper playlist; to be populated\]

### Demuxing

All video streams should be demuxed with Eac3to

#### Guide

\[How to demux with eac3to to be populated\]

### Remuxing

#### Guide

\[How to remux with mkvtoolnix to be populated\]

- Do not set a Delay
- Do not set a Stretch By value
- Do not set a default duration/FPS
- Do not include a timestamp file
- Do not check the Fix Bitstream timing info checkbox
- Do not explicitly set an Aspect Ratio or the Display Width/Height
- Do not set any cropping
- Do not set any stereoscopy
- Set NALU Size Length as Do Not Change
- Set Indexing (Cues) as Determine Automatically
- Do not set Additional Options
- Do not add Segment Info
- For Split Mode, set as “Do Not Split”
- Do not add any File Segment Linking

### Container

All Remuxes must be in the MKV container

#### Guide

\[How to set the container to MKV to be populated\]

### MKV Attributes

This section describes specific attributes in the MKV container. One table includes all attributes that are always, or sometimes, populated for the video track and another includes all attributes which are never populated for the video track

#### Populated

<table class="c28"><tbody><tr class="c8"><td class="c13 c43" colspan="1" rowspan="1"><p class="c3"><span class="c45 c44 c36">Attribute</span></p></td><td class="c37 c43" colspan="2" rowspan="1"><p class="c3"><span class="c45 c44 c36">Description</span></p></td><td class="c13 c43" colspan="1" rowspan="1"><p class="c3"><span class="c45 c44 c36">Example</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Track Number</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This is the master track number in comparison to all included tracks (Video, Audio, Subtitle, etc). This should always be set as 1 for the video track</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_9eys0cr09my9-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">1</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Track UID</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This is a unique Id for the Track. It should automatically be populated and shouldn’t need to be changed</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_vfecwhqlh3ss-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">12837528612295341791</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Default Track Flag</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should always be set to Yes for the Video Track</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_sifblxgebbdf-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">Yes</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Default Duration</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and shouldn’t need to be changed</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_40a8qlhn1rm0-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">41708333</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Name</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c21"><a class="c20" href="#h.lfm8s4km05kw">See Video Track Naming Conventions</a></span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_thot4jv6tuse-0 start"><li class="c3 c5 li-bullet-0"><span class="c21"><a class="c20" href="#h.lfm8s4km05kw">See Video Track Naming Conventions Examples</a></span><span>&nbsp;for the applicable Movie or TV Episode type</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Language</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This is used to identify the language of the video. It should correspond to the primary language that the video appears to use</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_o3qkbt6qv1av-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">English</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="7"><p class="c3"><span class="c1">Language (IETF BCP 47)</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This is used to further identify the language of the Video.</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">See Below</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Language</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is the primary language that the video appears to use</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_gz9fy7fegegm-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">English</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Extended Subtags</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is never populated</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Script</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is never populated</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Region</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is never populated</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Variants</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is never populated</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Private Use</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is never populated</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c21"><a class="c20" href="https://www.google.com/url?q=https://www.matroska.org/technical/codec_specs.html&amp;sa=D&amp;source=editors&amp;ust=1648475533266371&amp;usg=AOvVaw0kZAdXuSzyrr82_ZLNQ-RR">Codec ID</a></span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and should not need to be changed</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_4gupi3kt7f14-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">V_MPEGH/ISO/HEVC</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Interlaced Flag</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This is the indication if the video is interlaced or not. If the video is not interlaced, this flag should not be populated. A value of “1” indicates interlaced is present</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_baqy2mcqax1j-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">1</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Pixel Width</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and should not need to be changed</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_ec2jeaink3wk-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">3840</span></li><li class="c3 c5 li-bullet-0"><span class="c1">1920</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Pixel Height</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and should not need to be changed</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_n7t9f38m1mfw-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">2160</span></li><li class="c3 c5 li-bullet-0"><span class="c1">1080</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Display Width</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and should not need to be changed</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_gy6zm6omwqs6-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">3840</span></li><li class="c3 c5 li-bullet-0"><span class="c1">1920</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Display Height</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and should not need to be changed</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_in1t5p37q5kn-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">2160</span></li><li class="c3 c5 li-bullet-0"><span class="c1">1080</span></li></ul></td></tr></tbody></table>

#### Never Populated

<table class="c28"><tbody><tr class="c14"><td class="c7 c43" colspan="1" rowspan="1"><p class="c3"><span class="c45 c44 c36">Attribute</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Color Matrix Coefficients</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Pixels to Remove in Chroma (Horizontally)</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Pixels to Remove in Chroma (Vertically)</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Pixels to remove in Cb (Horizontally)</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Pixels to remove in Cb (Vertically)</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Horizontal Chroma Siting</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Vertical Chroma Siting</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Color Range</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Transfer Characteristics</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Color Primaries</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Maximum Content Light</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Maximum Frame Light</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Chromaticity red X</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Chromaticity red Y</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Chromaticity green X</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Chromaticity green Y</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Chromaticity blue X</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Chromaticity blue Y</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: White Point X</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: White Point Y</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Minimum Luminance</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Projection Type</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Projection-Specific Data</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Projection’s Yaw Rotation</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Projection’s Pitch Rotation</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video: Projection’s Roll Rotation</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Track Enabled Flag</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Forced Display Flag</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Minimum Cache</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Maximum Cache</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Codec-Inherent Delay</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Crop Left</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Crop Top</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Crop Right</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Crop Bottom</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Aspect Ratio Type</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Field Order</span></p></td></tr><tr class="c14"><td class="c7" colspan="1" rowspan="1"><p class="c3"><span class="c1">Video Stereo Mode</span></p></td></tr></tbody></table>

#### Guide

\[How to set the MKV Attributes to be populated\]

### Chapters

#### Requirements

- Chapters should be loaded directly from the MPLS file using MKVToolNix. Do not adjust the chapter timings.
- Chapter names should be taken from the Disc by playing the disc in VLC. If the Disc does not play in VLC, send a note to the group to identify a new software to be used for opening the disc.
- All chapter names must be in English. This is regardless of the native language of the film, the primary Audio for the film or any other consideration
- If there are no chapter names present then set the names with the prefix of “Chapter”. Example: Chapter 1, Chapter 2, Chapter 3, etc

- Chapters are deemed as not present when the Source disc does not contain chapter names AND a secondary source disk also does not contain chapter names. The secondary source disk should be of 1080p if the original source disk was 4K.

- Character Set should always be set as UTF-8
- Do not set the Extended Subtags,Script, Region, Variants or Private Use fields in the Language selection

#### Guide

- Run eac3to to find the mpls file containing the movie (and chapters) We can see that 00000.mpls is the file needed (based on runtime)\]![](images/image7.png)
- Step 2: MKVToolNix GUI --> Chapter Editor --> Open supported chapter file format Select the file from above (00000.mpls) This will load the chapter timings as per the BD\]![](images/image6.png)![](images/image2.png)![](images/image5.png)
- Step 3: Now to get the chapter names, simply open the disk using VLC or similar software If VLC make sure to select the right type of disk.![](images/image1.png)![](images/image8.png)
- Step 4: Run thru the menu to reach the chapter selection. Note down the chapter names and manually enter them in chapter editor![](images/image3.png)![](images/image4.png)
- In the example given, the chapter names were in italian so I had them translated by a native speaker (Use google translate ONLY AS A LAST OPTION as the translations are usually off)

## \[ Audio \]

- When the source contains a TrueHD audio track, an additional AC-3 track should also be included
- When the source contains a DTS-HD audio track, the core DTS track should not be extracted into a separate audio track.
- A TrueHD audio track and DTS-HD audio track should not both be included for the same Language and Content Type.
- Audio Tracks should be ordered in Alphabetical order (as read in English). When multiple audio tracks exist for the same language, the following track order should be used

- Main
- Descriptive Audio
- Commentary

- For multiple commentary tracks, they are alphabetical based on the commentary track name

- “Standard” Releases

- Only a Primary and English audio track should be included for the main video content.

- A Primary track should only be included in addition to an English audio track if the video was released primarily in a non-english language

- Example: Pan’s Labrynth would be permitted to have both a Spanish language track and an English Language track. Gladiator would only be permitted to have an English Language track.

- The requirements around TrueHD and DTS-HD tracks apply in addition to the Primary/English track requirements.

- If Commentary tracks are available, an additional Primary and English audio track can be included for each commentary track
- If descriptive audio tracks are available, an additional Primary and English audio track can be included

- “MULTi” Releases

- All audio tracks should be included, including any languages and commentaries.

- Audio tracks from other sources are permitted (and encouraged) to be included, but must be checked to ensure they sync properly with the video
- Audio tracks from other sources can only be included when one of the following is met

- A language is present in a different source that is not present in the current source
- An audio track in a different source has an object based (DTS:X, Atmos, etc) track and the best track in the same language in the current source does not
- Additional, unique, commentary exists in a different source
- A unique implementation of an existing audio track and language exists on a different source. For Example: SDH

- No compression (ex: ZLIB) should be used when remuxing audio tracks

### MKV Attributes

This section describes specific attributes in the MKV container. One table includes all attributes that are always, or sometimes, populated for every audio track and another includes all attributes which are never populated for any audio track

#### Populated

<table class="c28"><tbody><tr class="c14"><td class="c13 c43" colspan="1" rowspan="1"><p class="c3"><span class="c45 c44 c36">Attribute</span></p></td><td class="c13 c43" colspan="1" rowspan="1"><p class="c3"><span class="c45 c44 c36">Description</span></p></td><td class="c13 c43" colspan="1" rowspan="1"><p class="c3 c18"><span class="c45 c44 c36"></span></p></td><td class="c13 c43" colspan="1" rowspan="1"><p class="c3"><span class="c44 c36 c45">Example</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Track Number</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be a sequential number following the previous track. The first audio track should be directly after the video track and should be track number 2. All subsequent audio tracks are numbered thereafter</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_l9wpvfmqrx70-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">2</span></li><li class="c3 c5 li-bullet-0"><span class="c1">3</span></li><li class="c3 c5 li-bullet-0"><span class="c1">4</span></li><li class="c3 c5 li-bullet-0"><span class="c1">5</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Track UID</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and should not need to be changed.</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_vcnqejpmqbi-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">5680250237692894760</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Default Track Flag</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">When an audio track exists which is the same language as spoken in the main film, that should be set as Yes. If there is no audio track that matches the original spoken language and there is an English audio track, that should be set as Yes. All other tracks and instances should be set as No</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_s0g5tqf29gia-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">Yes</span></li><li class="c3 c5 li-bullet-0"><span class="c1">No</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Default Duration</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and should not need to be changed</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_5bw4pg6ejd75-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">10666667</span></li></ul></td></tr><tr class="c14"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Name</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c21"><a class="c20" href="#h.l7si1zyqtwk">See Audio Track Naming Conventions</a></span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_thot4jv6tuse-0"><li class="c3 c5 li-bullet-0"><span class="c21"><a class="c20" href="#h.qe0ehl1agfgm">See Audio Track Naming Conventions Examples</a></span><span class="c1">&nbsp;</span></li></ul></td></tr><tr class="c14"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Language</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This is used to identify the language of the audio track. It should correspond to the primary language that the audio appears to use</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_o3qkbt6qv1av-0"><li class="c3 c5 li-bullet-0"><span class="c1">English</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="7"><a id="id.lzdi2iszwcrd"></a><p class="c3"><span class="c1">Language (IETF BCP 47)</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This is used to further identify the language of the Audio track.</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">See Below</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Language</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is the primary language that the audio appears to use</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_gz9fy7fegegm-0"><li class="c3 c5 li-bullet-0"><span class="c1">English</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Extended Subtags</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">No use cases to populate this have yet been identified</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Script</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">No use cases to populate this have yet been identified</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Region</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span>This is populated if there are two or more subtitles of the same language that are part of the same Audio track and are </span><span class="c23 c54">spoken differently</span><span class="c1">. For example, there may be two main feature audio tracks both recorded in Spanish. One uses the European (Castilian) dialect and the other uses the Latin American dialect. This would require more than just the language of Spanish to differentiate the two. However, if one audio track is for the main feature and another is for commentary or SDH, or forced dialogue, then no additional information is required, even if they differ in their dialects.</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_seyyorooi6pz-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">419</span></li><li class="c3 c5 li-bullet-0"><span class="c1">CA</span></li><li class="c3 c5 li-bullet-0"><span class="c1">FR</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Variants</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">No use cases to populate this have yet been identified</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Private Use</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">No use cases to populate this have yet been identified</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c14"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c21"><a class="c20" href="https://www.google.com/url?q=https://www.matroska.org/technical/codec_specs.html&amp;sa=D&amp;source=editors&amp;ust=1648475533295491&amp;usg=AOvVaw2snnUb6Ij7aE_diHKkAiob">Codec ID</a></span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and should not need to be changed</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_4gupi3kt7f14-0"><li class="c3 c5 li-bullet-0"><span class="c1">A_DTS</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Audio Sampling Frequency</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and shouldn’t need to be changed. If needed, it can be obtained from MediaInfo</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_wew7wa9gyd25-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">48000</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Audio Channels</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and shouldn’t need to be changed. If needed, it can be obtained from MediaInfo. This combines all channels into a single number. 5.1 = 6, 5.1.4 = 9, 7.1 = 8, 2.0 = 2</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_m5ht16rd67ai-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">2</span></li><li class="c3 c5 li-bullet-0"><span class="c1">6</span></li><li class="c3 c5 li-bullet-0"><span class="c1">8</span></li><li class="c3 c5 li-bullet-0"><span class="c1">10</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Audio Bit Depth</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and shouldn’t need to be changed. If needed, it can be obtained from MediaInfo</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_n5hh7jax2w6q-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">24</span></li></ul></td></tr></tbody></table>

#### Never Populated

- Track Enabled Flag
- Forced Display Flag
- Codec-Inherent Delay
- Audio Output Sampling Frequency

#### Guide

\[How to set the MKV Attributes to be populated\]

## \[ Subtitles \]

### Requirements

- All subtitle tracks from the source should be included in any Remux.
- Subtitles from additional sources are permitted only for MULTi releases

- These subtitles must be double checked to ensure they sync properly
- Subtitles from other sources can only be included if they meet one of the following requirements

- A subtitle track language exists in another source that does not exist in the current source
- A content type exists in a different source than what exists in the current source, for the same language. Example: SDH or additional Commentary

- Further discussion is required on how, if at all, these additional tracks should be identified. If a release aims to include these tracks, start a discussion around this topic

- All subtitle tracks should be in either the PGS format or the SSA/ASS format depending on the source. No changes to the original codec are to be applied.
- All subtitles in the remuxed video should have the same graphical rendering as the subtitles when played as part of the original disc (or via ISO/BDMV)
- Subtitle tracks should be listed in Alphabetical order by language (as read in English). Within each language, the order should be

- Forced Narrative
- Main
- SDH
- Commentary

- When multiple commentaries exist, they are ordered alphabetically by track name

- No compression (ex: ZLIB) should be used when remuxing subtitle tracks
- If hardcoded subtitles exist, ensure that any additional subtitle tracks do not overlap with the hardcoded subtitles

### MKV Attributes

This section describes specific attributes in the MKV container. One table includes all attributes that are always, or sometimes, populated for every subtitle track and another includes all attributes which are never populated for any subtitle track

#### Populated

<table class="c28"><tbody><tr class="c14"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Attribute</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Description</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3 c18"><span class="c1"></span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Example</span></p></td></tr><tr class="c14"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Track Number</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be a sequential number following the previous track. The first subtitle track should be directly after the last audio track. All subsequent subtitle tracks are numbered thereafter</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_ng409m2vh3io-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">3</span></li><li class="c3 c5 li-bullet-0"><span class="c1">4</span></li><li class="c3 c5 li-bullet-0"><span class="c1">5</span></li><li class="c3 c5 li-bullet-0"><span class="c1">6</span></li></ul></td></tr><tr class="c14"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Track UID</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and should not need to be changed.</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_l741fwlii736-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">8091695627121434947</span></li></ul></td></tr><tr class="c14"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Default Track Flag</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">When the video is an English video, the main English subtitle track should have this set as Yes and all other tracks should have this set as No. When the video is a foreign language video, the primary language that corresponds to the video should have that subtitle track set as Yes and all others set as No.</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_wryjfg59pb0c-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">Yes</span></li><li class="c3 c5 li-bullet-0"><span class="c1">No</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Forced Display Flag</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c2"><span class="c1">This is used to mark all subtitle tracks that correspond to subtitles that are the same language as an Audio Track language and are expected to be played when foreign language is spoken as part of the primary audio track. Forced subtitles should be set for all foriegn languages, not just for English subtitles. For non-forced subtitle tracks, this should be set as No.</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_ewue8wphkbl3-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">Yes</span></li><li class="c3 c5 li-bullet-0"><span class="c1">No</span></li></ul></td></tr><tr class="c14"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Name</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c21"><a class="c20" href="#h.m0htc04nva8x">See Subtitle Track Naming Conventions</a></span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_thot4jv6tuse-0"><li class="c3 c5 li-bullet-0"><span class="c21"><a class="c20" href="#h.vzzvkx4xr3a1">See Subtitle Track Naming Conventions Examples</a></span><span class="c1">&nbsp;</span></li></ul></td></tr><tr class="c14"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Language</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This is used to identify the language of the subtitle track. It should correspond to the primary language that the subtitles appear to use</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_o3qkbt6qv1av-0"><li class="c3 c5 li-bullet-0"><span class="c1">English</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="7"><a id="id.b64fbylquu9u"></a><p class="c3"><span class="c1">Language (IETF BCP 47)</span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This is used to further identify the language of the subtitle track.</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">See Below</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Language</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">This is the primary language that the audio appears to use</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_gz9fy7fegegm-0"><li class="c3 c5 li-bullet-0"><span class="c1">English</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Extended Subtags</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">No use cases to populate this have yet been identified</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Script</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span>This is populated if there are two or more subtitles of the same language that are part of the same Audio track and are </span><span class="c23 c54">written differently</span><span class="c1">. For example, there may be the main feature audio track which has both Simplified and Traditional Chinese subtitles. This would require more than just the language of Chinese. However, if one subtitle track is for the main feature and another is for commentary or SDH, or forced dialogue, then no additional information is required, even if they differ in their written representation.</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_6mxoqx956bvd-0 start"><li class="c3 c5 li-bullet-0"><span class="c1">Hant - Traditional Chinese</span></li><li class="c3 c5 li-bullet-0"><span>Hans - Simplified Chinese</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Region</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span>This is populated if there are two or more subtitles of the same language that are part of the same Audio track and are </span><span class="c23 c54">spoken differently</span><span class="c1">. For example, there may be two main feature audio tracks both recorded in Spanish. One uses the European (Castilian) dialect and the other uses the Latin American dialect. This would require more than just the language of Spanish to differentiate the two. However, if one audio track is for the main feature and another is for commentary or SDH, or forced dialogue, then no additional information is required, even if they differ in their dialects.</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_seyyorooi6pz-0"><li class="c3 c5 li-bullet-0"><span class="c1">419</span></li><li class="c3 c5 li-bullet-0"><span class="c1">CA</span></li><li class="c3 c5 li-bullet-0"><span>FR</span></li></ul></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Variants</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">No use cases to populate this have yet been identified</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c8"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">Private Use</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c1">No use cases to populate this have yet been identified</span></p></td><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c34">NULL</span></p></td></tr><tr class="c14"><td class="c13" colspan="1" rowspan="1"><p class="c3"><span class="c21"><a class="c20" href="https://www.google.com/url?q=https://www.matroska.org/technical/codec_specs.html&amp;sa=D&amp;source=editors&amp;ust=1648475533312845&amp;usg=AOvVaw3Sc0RCtnwzbs3cQB-p4GlG">Codec ID</a></span></p></td><td class="c37" colspan="2" rowspan="1"><p class="c3"><span class="c1">This should be auto populated and should not need to be changed</span></p></td><td class="c13" colspan="1" rowspan="1"><ul class="c17 lst-kix_4gupi3kt7f14-0"><li class="c3 c5 li-bullet-0"><span class="c1">S_HDMV/PGS</span></li><li class="c3 c5 li-bullet-0"><span class="c10 c44 c61">S_TEXT/SSA</span></li><li class="c3 c5 li-bullet-0"><span class="c61 c10 c44">S_TEXT/ASS</span></li></ul></td></tr></tbody></table>

#### Never Populated

- Track Enabled Flag
- Minimum Cache
- Maximum Cache
- Default Duration
- Codec-Inherent Delay

#### Guide

\[How to set the MKV Attributes to be populated\]

### Forced

Forced subtitles are often present when a character deliberately speaks in a language that is different than the primary language spoken in the rest of the audio track. In these cases, subtitles are shown even when not independently selected before playback. These subtitles are considered Forced and are expected to be included as a separate subtitle track in any remuxes. In any instances where forced subtitles are suspected, great caution should be used to ensure the subtitles are properly included as a forced track as there are many different methods for indicating a forced subtitle needs to be shown. A notoriously difficult example is the movie Avatar (2009)

When a subtitle track is demuxed with EAC3TO, if the output indicates the presence of Forced Subtitles, and an Audio Track with the same language is also in the release, then the Forced Subtitles must be extracted to their own Subtitle track (Primarily for MULTi releases)

#### Guide

\[How to check a if a file contains forced subtitles, and how to extract them, to be populated\]

- Step 1:

\[How to separate Forced subtitles into their own track to be populated\]

## \[ Container \]

- All Remuxes will utilize the corresponding Matroska container.
- Any 3d remuxes will require durther discussion

## \[ Extras \]

Extras should not be released as part of the same torrent as the main video file and must be released under a separate EXTRAS torrent. Further discussion is needed before any EXTRAS torrent is released. If a desire exists to release an EXTRAS torrent, start a discussion on this topic with the internal team.

## \[ Directories\]

This section describes the requirements around any directory structure for the packaging of the torrent

- Generally, when two or more files are included in a torrent, they must be included underneath a common directory
- Generally, when only a single file is included in a torrent, it should not be included underneath a common directory
- All movie remuxes are expected to be only a single file and as such, should not be underneath a separate directory
- All TV remuxes are expected to be season packs and as such, should always be underneath a separate directory.
- There should be no more than a single directory in any one torrent.
- See [Directory Naming Conventions](#h.z90vfgnt31br) for how to name the directory

## \[ Future Ideas \]

- Include Chapter names besides just English

- Not included initially as it may have unknown negative consequences to Plex or other systems.

# \+ \[ ENCODES \] +

# \+ \[ FULL DISCS\] +

### Requirements

- ISOs are permitted only for 3D content.
- Full folder structures are required for all non-3D content
- All folder and files must be untouched after ripping
