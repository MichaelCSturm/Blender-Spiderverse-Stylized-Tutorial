# Spider-verse tutorial in Blender 3.3

Auhor: Michael Sturm

Summary: In this tutorial I explain how to UV unwrap a mesh, set up an general comicbook shader and animation on twos in Blender 3.3. The intended audience is for creative types who lack much knowledge in blender yet still want to make an animation effective and very stylized. Following this tutorial should only take about 30 minutes yet a distinct look should be produced.



Before:

![untitled4](https://user-images.githubusercontent.com/59833741/206824634-fe4543a8-e440-4048-8466-a3cc4c8df6dc.png)

After:

![after](https://user-images.githubusercontent.com/59833741/206824650-228f992a-9b62-47a0-b514-42138c551a2f.png)


This tutorial assumes the user knows how to perform basic blender navigation 
# Step one Uv unwrap.

Click on your mesh and head to UV editing.

<img width="517" alt="step one" src="https://user-images.githubusercontent.com/59833741/206823631-d9d736c3-7b1e-4800-8c57-fb5a9e9379ab.PNG">

Go to editing mode then press the key A on your keyboard to select all

<img width="387" alt="step 2" src="https://user-images.githubusercontent.com/59833741/206823707-c623991f-a508-4d35-9cb9-851e401641dd.PNG">

Save. Seriously press save.

Hit unwrap then unwrap again.

# Step two go to shaders tab.
If you cant find it it's here

<img width="789" alt="Shaders" src="https://user-images.githubusercontent.com/59833741/206824090-13b0ab2a-2168-41f9-9e8b-4d3393202aef.PNG">

Using shift A and allot of editing. Input these shaders. The multiply nodes are labeled under math nodes. Obviously the coloring for this material is an example. Set these nodes for the spefic colors as needed. If you'd like to add a texture paint to put this effect on add a mix shader then mix this entire daisychain with an image texture of your texture paint. REMEMBER IT'S POSSIBLE TO ASSIGN SHADERS TO SPEFIC FACES OF MESHES AND KEYFRAME IT! THEREBY SETTING THIS AS A EASY WAY TO COMICBOOK SHADE SOMETHING

<img width="539" alt="step 3" src="https://user-images.githubusercontent.com/59833741/206824046-448e7006-84de-44e9-96e4-54bcb246d22d.PNG">

![0001-0040](https://user-images.githubusercontent.com/59833741/206824452-1f81cba2-507c-4190-be7e-306687bdd3d0.gif)

If you wanted to continue down this path of more like Spider-verse stylized animation heres a more advanced technique.

Before: 

![0001-0040(1)](https://user-images.githubusercontent.com/59833741/206824949-6e932f22-f4f5-4a8d-93c7-423e6cbca51f.gif)

Little too clean looking for a comic book stylized animation right?

Into the spiderverse animated characters on twos to indicate they're struggling while also animating other characters on ones to show confidence and authority. 

Theres no other clearier scene then the forest chase scene.

https://youtu.be/gnGcpzpgaFc?t=61

Older spiderman is animated on ones while Miles is animated on twos.

Characters can go from extremely choppy to smoothe to indicate their feeling to the audience without saying or animating anything.

# How can we do that?

To set up an animation on twos look at your timeline 

<img width="392" alt="timeline" src="https://user-images.githubusercontent.com/59833741/206825135-0770a9a4-3b43-4020-9391-8e436a82ad8d.PNG">

Select all the animation keyframes.

Then select Object or charcter. 

<img width="648" alt="select" src="https://user-images.githubusercontent.com/59833741/206825236-0c2cf3c8-437e-42ad-9081-33aad31cd3a1.PNG">

Then select animation and bake animation.

<img width="517" alt="happy" src="https://user-images.githubusercontent.com/59833741/206825319-73493b51-a211-4e25-a510-ed8b28b67591.PNG">

Then still having all these frames selected, Change the interpolation mode to constant

You do this by pressing T and hitting constant(Another of doing this is going to graph editor)

![0001-0040(2)](https://user-images.githubusercontent.com/59833741/206825504-157f4609-c297-4b41-a99a-ea830179d885.gif)

Beatiful! 
