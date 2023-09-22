# Video-segmentation-for-Kitchen

## Week 1
Step 1 : Read relevant literature (Dataset papers: EPIC Kichens or Assembly101; Action segmentation papers: BIT or DiffAct; Large model: Kosmos-2).

Briefly get familar with:
- EPIC Kitchen: https://epic-kitchens.github.io/2023
- Assembly 101: https://assembly-101.github.io/

Check the demo code for Kosmos-2:
- Kosmos-2 demo: https://huggingface.co/ydshieh/kosmos-2-patch14-224

Step 2 : Try the zero-shot learning ability of Kosmos-2 on our [data](https://drive.google.com/drive/folders/1yrAanzKUw7_w5rAmeHxkS-OzGdmqVpwF?usp=sharing): Ommlet session OH0037\2023_05_10_15_17_17 and Ratatouille session YH0033\2023_05_03_09_14_42. 

Things to think:
- How to leverage the zero-shot learning ability of Kosmos-2 to help the labeling.
- Anything required to improve for our [action list](https://drive.google.com/drive/folders/1yrAanzKUw7_w5rAmeHxkS-OzGdmqVpwF?usp=drive_link).

## Week 2 - 5
Step 3 : Annotate one action video based on our action list

Step 4 : Select the best-fitted method, reproduce the result, and visualize the outputs.

Step 5 : Apply zero-shot learning of the selected model to our data.

## Week 5 - 8
Step 6 : Verify the quality of the labeled action from the annotation company. Compared with his annotation.

Step 7 : Help to check the processed data (synchronized videos, 3D poses, and action annotations)

Step 8 : Statistics of the labeled actions.

## Week 8 - 12
Step 9: Write the action data loading code for our dataset

Step 10: Benchmark the selected model on our dataset.

## Week 13 :
Step 11: Clean Code and prepare presentation 
