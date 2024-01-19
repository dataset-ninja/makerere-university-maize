The **Makerere University Maize Image Dataset** was created to provide an open, well-labelled, sufficiently curated and accessible maize image dataset. Data scientists, researchers, and the broader machine learning community can use the dataset for various machine learning experiments to build maize crop disease diagnosis and spatial analysis solutions.

## Motivation

While the agricultural sector holds a prominent position in the national economic development agenda of Sub-Saharan Africa, it grapples with challenges posed by crop pests and diseases, particularly affecting crucial food security crops such as Maize. Over the past decade, Maize Leaf Blight disease, also known as Northern Corn Leaf Blight, has emerged as a significant threat in lowland agro-ecological zones. Simultaneously, Maize Streak Disease, caused by the Maize Streak Virus, ranks as the third most serious ailment impacting maize in Sub-Saharan Africa. The prevalence of these diseases has significantly hampered maize yields.

The current approach to data collection and crop pest and disease diagnosis is undergoing a transition from relying on visible symptoms for disease identification to employing data-driven solutions that incorporate machine learning and computer vision techniques. Despite these advancements, the image data previously collected remains inadequately curated, prepared, and shared within the broader community.

## Dataset Creation

The dataset was created by scientists from the Makerere Artificial Intelligence Lab and the National Crops Resources Research Institute (NaCRRI) in Namulonge,
Uganda. NaCRRI is an institute of the National Agricultural Research Organisation (NARO) in charge of crop research.
Each instance is associated with a class label based on the status of the crop: healthy or diseased. The dataset consists of a crop image with an image status, i.e., ***healthy***, Maize Leaf Blight(***mlb***), Maize Streak Virus(***msv***). 

<img src="https://user-images.githubusercontent.com/120389559/298060192-0d850509-90cb-40f9-9b2a-d2c69c181fc0.png" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;">Maize Data Labels.</span>

The dataset contains maize image data collected across the different regions in Uganda. The dataset has image samples collected from significant maize growing districts selected with the guidance of agricultural experts to obtain a representative dataset. The data consists of raw image data. Each image data point is accompanied with attributes; the crop ***variety***, plant ***age***, ***district***, ***subcounty***, and the ***datetime*** of image capture. There are no relationships between the different image instances in the dataset.

## Collection Process

The maize image data was collected using mobile phones from farmer gardens. The gardens were identified within the maize growing prominent districts across the four regions in Uganda. The data was collected using the Adsurv application, which is a mobile application that enables crowdsourcing of crop disease data from farmers’ gardens. Adsurv application was installed on mobile phones/tablets used during the data collection process.

Individuals involved in the data collection process included a team of researchers from the Makerere Artificial Intelligence Lab, an agricultural expert affiliated with the cereals program at the National Crops Resources Research Institute (NaCRRI), and a district agricultural officer.

The authors conducted thorough data cleaning procedures, eliminating blurry images, those captured under direct sunlight, and resolving inconsistencies in resolution. In certain instances, data collectors manually input image attribute variables such as crop variety. Modifications to predetermined attributes like districts and sub-counties were made during the data collection phase, leading to inconsistencies in the generated dataset. These inconsistencies manifested as variations in reporting and corrections to district/sub-county information when data had been collected from a different location. The resolution of these inconsistencies was addressed during the subsequent data cleaning process.
