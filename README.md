
In today’s digital era, an enormous amount of information is stored in document form,
including scanned images, PDFs, and digital reports. These documents often contain a mix
of textual and graphical elements such as tables, charts, diagrams, and images. Extracting
meaningful information from these documents is a very important task in fields such as
education, research, business, and legal compliance. However, detecting and analyzing
graphical objects within these documents is such a challenge because of the following
reasons:<br/>
• Diverse Document Formats: Documents come in various formats and layouts, making it difficult to develop a one-size-fits-all solution.<br/>
• Complex Structures: Graphical objects are often embedded alongside text, with
varying sizes, resolutions, and orientations.<br/>
• Manual Processing Limitations: Relying on human effort to manually identify and
extract graphical content is time consuming and inefficient, especially when dealing
with large-scale document collections.<br/>
Given these challenges, there is a clear need for an automated system capable of
accurately detecting and extracting graphical objects from documents, which will provide
several benefits:<br/>
• Efficiency: Automation significantly reduces the time and effort required to process
large volumes of documents.<br/>
• Accuracy: Object detection models are capable of achieving high precision, minimizing errors associated with manual extraction.<br/>
• Scalability: Automated solutions can handle a large amount of documents, making
them suitable for enterprise-level applications.<br/>
To address these needs, this project utilizes the DEtection TRansformer (DETR)
model. DETR is a new approach to object detection, it is the result of the Facebook
Researcher Team. DETR leverages the power of transformers to directly predict bounding
boxes and class labels for objects in an image, eliminating the need for traditional region
proposal methods. Although DETR does not have a really impressive performance, it is
a promising approach and can be further developed to be state-of-the-art model with
highest precision.<br/>
You can get access to the Project on Google Colab via this link:<br/>
https://colab.research.google.com/github/chaunguye/chaunguye/blob/main/notebooks/train-huggingface-detr-on-custom-dataset.ipynb
