# Zebracat
Creating Video DataLoader
In the test.py file you can see a code which test the dataloader.
I design dataloader based on what I understand from the explanation of the task. I add some option like shuffling, getting batch size, and returning in PyTorch tensors.

I think one of the weakness of this dataloader is that when we want to create a batch with N random frame of each video, to have access to the selected frame we need to read all frame before the maximum number of the list of selected frames. It can be like a waste of time. However, since I think that maybe I have not understand correctly the task, I am not sure about my response. 
