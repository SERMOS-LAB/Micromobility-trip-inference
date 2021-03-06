# Micromobility Trip Origin and Destination Inference Using General Bikeshare Feed Specification (GBFS) Data

## Cite our paper
Xu, Y., Yan, X., Sisiopiku, V. P., Merlin, L. A., Xing, F., & Zhao, X. (2022). Micromobility trip origin and destination inference using general bikeshare feed specification (gbfs) data. Transportation research record.

##
Emerging micromobility services (e.g., e-scooters) have a great potential to enhance urban mobility but more knowledge on their usage patterns is needed. The General Bikeshare Feed Specification (GBFS) data are a possible source for examining micromobility trip patterns, but efforts are needed to infer trips from the GBFS data. Existing trip inference methods are usually based upon the assumption that the vehicle ID of a micromobility option (e-scooter or e-bike) does not change, and so they cannot deal with data with vehicle IDs that change over time. In this study, we propose a comprehensive package of algorithms to inferOD pairs from GBFS data with static vehicle ID and unlinked trip origins and destinations from GBFS data with resetting and dynamic vehicle ID. We implement the algorithms in Washington D.C. by analyzing one-week (last week of February 2020) of GBFS data published by six vendors, and we evaluate the inference accuracy of the proposed algorithms by R-squared, mean absolute error, and sum absolute error. We find that the R-squared measure is larger than 0.9 and the MAE measure is smaller than 2 when the algorithms are evaluated with a 400m x 400m grid. The absolute errors are relatively larger in the downtown area, and the inference error is relatively high during early morning and early night. The accuracy of the trip-inference algorithms is sufficiently high for most practical applications. 

- Inference_Algorithms.ipynb: Code for inference algorithms.
- Demo_Data_Static.csv: Demo data with Static Vehicle ID.
- Demo_Data_Resetting.csv: Demo data with Resetting Vehicle ID.
- Demo_Data_Dynamic.csv: Demo data with Dynamic Vehicle ID.
