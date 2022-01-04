# Ring Art Gallery

This instillation art piece aimed to bring awareness to Amazon products’ data collection (specifically the Ring doorbell). The average consumer believes that surveillance data has little-to-no value. To challenge this mentality, we used a machine learning model to render Ring doorbell surveillance images in the style of famous artwork. Thus, our exhibit displays Ring doorbell images as priceless works of art.

This project utilizes the ring_doorbell api to interact with a Ring doorbell. When a user presses the doorbell, an image is downloaded from the Ring doorbell. Face cropping is then attempted. After, the image goes through style transfer via the STROTTS model (https://arxiv.org/abs/1904.12785), the final results of which can be seen below:

Content image: 

![scene_me](https://user-images.githubusercontent.com/43860983/148047520-cd6c8608-cb13-46a9-9619-e8778a327934.jpg)


Style image:

![style](https://user-images.githubusercontent.com/43860983/148047531-96608354-4c94-4211-9312-ed1a2cefb6dc.jpg)

Result:

![main_portrait](https://user-images.githubusercontent.com/43860983/148047543-a41da29d-d9c6-443e-9676-853c282c9a32.png)
