Supplementary materials for the paper: ATTENTION-BASED CROSS-MODAL FUSION FOR AUDIO-VISUAL VOICE ACTIVITY DETECTION IN MUSICAL VIDEO STREAMS

<p>Please see here(https://yuanbo2021.github.io/Attention-based-audio-visual-VAD/) for video demos.</p>

<h3 align="left"><a name="part3">1. The proposed attention-based AVVAD (ATT-AVVAD) framework.</a><p></p></h3> 

<p><div align="center">
<img src="AVVAD-framework.PNG" width=100%/>
</div>

<p align="center"> The proposed attention-based AVVAD (ATT-AVVAD) framework consists of the audio-based module (audio branch), image-based module (visual branch), and attention-based fusion module. The audio-based module produces acoustic representation vectors for four target audio events: Silence, Speech of the anchor, Singing voice of the anchor, and Others. The image-based module aims to obtain the possibility of anchor vocalization based on facial parameters. Finally, we propose an attention-based module to fuse audio-visual information to comprehensively consider the bi-modal information to make final decisions at the audio-visual level.</p>

</p>

<h3 align="left">2. Visualization of core representation vectors distribution after attention-based fusion from a test sample using t-SNE.<p></p></h3> 

<p align="center"> The vectors in subgraph (a) are from the audio branch, vectors in subgraph (b) are from audio-visual modules after attention-based fusion.</p>

<p><div align="center"> 
<h3> Sample 1 </h3> <img src="after-attention-sample0.PNG"  width=60%/>
<h3> Sample 2 </h3> <img src="after-attention-sample1.PNG"  width=60%/>
<h3> Sample 3 </h3> <img src="after-attention-sample2.PNG"  width=60%/>
<h3> Sample 4 </h3> <img src="after-attention-sample3.PNG"  width=60%/>
</div>
</p>

<h3 align="left">3. Visualization of acoustic representation vectors and visual vocalization vector distribution from a test sample using t-SNE.<p></p></h3> 

<p align="center"> The vector (black dots) representing the vocalizing of the anchor is distributed on the side representing the voices of the anchor (green dots for singing, red dots for speech).</p>


<p><div align="center"><h3> Sample 5 </h3> <img src="audio-visual0.PNG" width=50%/></div></p>
<p><div align="center"><h3> Sample 6 </h3> <img src="audio-visual1.png" width=60%/></div></p>
<p><div align="center"><h3> Sample 7 </h3> <img src="audio-visual2.png" width=60%/></div></p>



<h3 align="left">4. For the source code, please check the Code.<p></p></h3>

<p>If you want to watch more intuitively, please see here: https://yuanbo2021.github.io/Attention-based-audio-visual-VAD/.</p>


<br>

<p>Please feel free to contact me if you have any questions.</p>

<p>Mail: Yuanbo.Hou@UGent.be</p>



