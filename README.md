# InsectDet: Harmful Pests Detection for protection of crops in real time

![val_batch2_pred](https://github.com/zappy586/InsectDet/assets/89218647/d45474d2-9bb4-455f-b9c6-9546913cd86c)


* This repo contains the model weights, training code and object detection code for InsectDet, which is an object detection model to detect 15 most common harmful insects or pests that harm crops and cause massive losses to farmers all year round.
* The model was trained on a <ins>GTX 1070 GPU for 100 epochs</ins> at 0.009 lr with AdamW optimizer with weight decay.
* The dataset was taken from a classification dataset from kaggle which was <ins>manually annotated by me<ins> on CVAT.
* The manually annotated dataset is available here on my GDrive: https://drive.google.com/drive/folders/1VvDf5_g6JZtDZ2cqaiCSnUSDTlXvYTRi?usp=sharing

The following are the 15 insects that can be detected with this model:
1. Killer Bees: These aggressive bees can disrupt pollination activities and pose a threat to farmworkers, making agricultural work hazardous.
2. Aphids: Aphids suck sap from plants, weakening them and transmitting plant diseases, which can lead to reduced crop yields and stunted growth.
3. Armyworms: Armyworms devour leaves, stems, and fruit, causing significant damage to crops such as corn, rice, and wheat, leading to yield loss and economic damage.
4. Brown Stink Bugs: These pests pierce plant tissue and suck out sap, causing deformation, discoloration, and reduced fruit quality in crops like soybeans, cotton, and tomatoes.
5. Cabbage Loopers: Cabbage loopers feed on leaves, causing extensive damage to cruciferous vegetables like cabbage, broccoli, and cauliflower, reducing marketable yields.
6. Citrus Canker: Citrus canker infects citrus trees, causing blemishes on fruit, premature fruit drop, and leaf loss, ultimately reducing fruit quality and yield.
7. Colorado Potato Beetles: These beetles defoliate potato plants, reducing photosynthesis and tuber development, leading to decreased yields and economic losses for potato farmers.
8. Corn Borers: Corn borers tunnel into corn stalks, weakening the plant's structural integrity and making it susceptible to lodging, reducing yield potential and grain quality.
9. Corn Earworms: Corn earworms damage corn crops by feeding on developing kernels, reducing yield and quality and facilitating the entry of fungi and bacteria into the ear.
10. Fall Armyworms: Fall armyworms consume foliage and reproductive structures of various crops, including corn, rice, and sorghum, causing significant yield losses and economic damage.
11. Fruit Flies: Fruit flies lay eggs in ripening fruit, leading to larvae infestation and fruit decay, rendering the fruit unmarketable and causing economic losses to fruit growers.
12. Spider Mites: Spider mites suck sap from plant tissues, causing leaves to become stippled, yellowed, and ultimately reducing photosynthesis and crop yields.
13. Thrips: Thrips feed on plant sap and transmit plant viruses, causing damage to leaves, flowers, and fruits, leading to reduced crop quality and market value.
14. Tomato Hornworms: Tomato hornworms consume tomato plant foliage and fruit, leading to defoliation, reduced fruit yield, and economic losses for tomato growers.
15. Western Corn Rootworms: These larvae feed on corn roots, impairing nutrient uptake and water absorption, resulting in reduced plant health, yield losses, and increased susceptibility to lodging.

