# Disco-Diffusion
Create Video to Disco Diffusion Video
# Disco Diffusion v5.2 - Warp by [Raj Rumel](https://facebook.com/mrrajrumel)
![visitors](https://visitor-badge.glitch.me/badge?page_id=sxela_ddwarp_colab)

This version improves video init. You can now generate optical flow maps from input videos, and use those to:
- warp init frames for consistent style
- warp processed frames for less noise in final video



##Init warping
The feature works like this: we take the 1st frame, diffuse it as usual as an image input with fixed skip steps. Then we warp in with its flow map into the 2nd frame and blend it with the original raw video 2nd frame. This way we get the style from heavily stylized 1st frame (warped accordingly) and content from 2nd frame (to reduce warping artifacts and prevent overexposure)

--------------------------------------

This is a variation of the awesome [DiscoDiffusion colab](https://colab.research.google.com/github/alembics/disco-diffusion/blob/main/Disco_Diffusion.ipynb#scrollTo=Changelog)

If you like what I'm doing you can
- follow me on [facebook](https://facebook.com/mrrajrumel)
- tip me on [twitter](https://twitter.com/mrrajrumel)


Thank you for being awesome!

--------------------------------------

