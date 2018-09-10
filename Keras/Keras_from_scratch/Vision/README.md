01 Basic CNN notebook
02 In notebook 01, we loaded the entire data in one go in the RAM. Here we will load chunk by chunk and then train the model. For this we use data generators
03 Pull data from folders on the fly and augment it in real time
04_1 Use pretrained network to extract features anf then feed these features to a FFN
05 We use  pretrained network to extract features on the fly and then pass them to Dense layers
06 We train not just dense layers but also fine tune last part of the pretrained network


Left overs:
07 Feature visualization
08 Filter visualization (Gradient ascent)
09 Class activation Maps (CAM)