# Toward Continuous-Time Representation of Human Motion
Weiyu Du, Oleh Rybkin, Lingzhi Zhang, Jianbo Shi <br/>
ECCV 2020 Workshop on Perception Through Structured Generative Models
(http://generativeperception.com/)<br/>
[link to paper](http://generativeperception.com/papers/toward_continuous_time_representations_of_human_motion.pdf)    
[link to video presentation](https://www.youtube.com/watch?v=EAOo-whr0HI&feature=emb_title)<br/>

## Motion Reconstruction
Motion reconstruction on AMASS test set, from left to right: ground truth, reconstruction with Sine Motion Encoding, reconstruction with Bezier Motion Encoding.   

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_sin_1_gt.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_sin_1_fitted.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_b_1_pred.gif" width="200" height="200"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_sin_8_gt.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_sin_8_fitted.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_b_8_pred.gif" width="200" height="200"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_b_10_gt.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_sin_10_pred.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_b_10_pred.gif" width="200" height="200"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_b_11_gt.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_sin_11_pred.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/recon/r_b_11_pred.gif" width="200" height="200"/>

## Motion Generation
Point-to-point motion generation on AMASS test set (30 frames), from left to right: ground truth, prediction by Sine Motion Encoding, prediction by Bezier Motion Encoding, latent linear interpolation baseline.  

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/60_gt.gif" width="150" height="150"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/60_pred_sin.gif" width="150" height="150"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/60_pred_b.gif" width="150" height="150"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/60_lerp.gif" width="150" height="150"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/42_gt.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/42_pred_sin.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/42_pred_b.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/42_lerp.gif" width="180" height="180"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/156_gt.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/156_pred_sin.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/156_pred_b.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/156_lerp.gif" width="180" height="180"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/40_gt.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/40_pred_sin.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/40_pred_b.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/40_lerp.gif" width="180" height="180"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/126_gt.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/126_pred_sin.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/126_pred_b.gif" width="180" height="180"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/amass/126_lerp.gif" width="180" height="180"/>

Point-to-point motion generation on Human3.6M test set (sub-sampled 5 times, 30 frames), from left to right: ground truth, prediction by Sine Motion Encoding(6 curves), prediction by Sine Motion Encoding(3 curves), prediction by Bezier Motion Encoding, latent linear interpolation baseline.  

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/26_gt.gif" width="120" height="120"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/26_pred.gif" width="120" height="120"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/26_pred_sin.gif" width="120" height="120"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/26_pred_b.gif" width="120" height="120"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/26_lerp.gif" width="120" height="120"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/7_gt.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/7_pred.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/7_pred_sin.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/7_pred_b.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/7_lerp.gif" width="130" height="130"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/5_gt.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/5_pred.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/5_pred_sin.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/5_pred_b.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/5_lerp.gif" width="130" height="130"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/36_gt.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/36_pred.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/36_pred_sin.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/36_pred_b.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/36_lerp.gif" width="130" height="130"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/71_gt.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/71_pred.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/71_pred_sin.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/71_pred_b.gif" width="130" height="130"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/h36m/71_lerp.gif" width="130" height="130"/>

## Variable Frequency Motion Generation
Motion generation at different lengths and frame rates on Human3.6M test set using Sine Motion Encoding (3 curves), from left to right: ground truth (30 frames, fps=12), prediction (30 frames, fps=12), prediction (60 frames, fps=24). 

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/frame/50_gt.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/frame/50_pred.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/frame/50_pred_long.gif" width="200" height="200"/>

<img src="https://github.com/WeiyuDu/motion_encode/blob/master/frame/64_gt.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/frame/64_pred.gif" width="200" height="200"/><img src="https://github.com/WeiyuDu/motion_encode/blob/master/frame/64_pred_long.gif" width="200" height="200"/>

