# Step CV-Pipeline: data_load

This component of the CV (computer vision) pipeline is responsible for loading data from various sources. This component ensures the receipt and preparation of data for further processing and analysis.
Includes the following stages:
- Data Source Selection: This stage involves selecting the source from which the data needs to be loaded.
Sources can be image or video files.
- Receiving Data: Once a source is selected, operations are performed to retrieve data from the selected source.
For example, for image or video files, this could be an operation of copying files from disk or loading a dataset from an external source.
- Data conversion. At this stage, data is converted from a non-standard format to the standard format of the SinaraML platform
- Transferring data to the next step of the pipeline: After loading and preparing the data, this stage of the cv pipeline transfers it to the next step of the pipeline, which includes other operations of analysis, processing and preparation of data for training.

In this example, it loads the dataset [`COCO`](http://images.cocodataset.org/).   
To launch and run cv-pipeline faster, we use the validation part of the dataset (~1 GB)
http://images.cocodataset.org/zips/val2017.zip
and annotations to them http://images.cocodataset.org/annotations/annotations_trainval2017.zip          
   
