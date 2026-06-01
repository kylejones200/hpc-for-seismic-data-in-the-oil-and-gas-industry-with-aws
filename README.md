# HPC for Seismic Data in the Oil and Gas Industry with AWS

Published: 2024-12-20
Medium: [https://medium.com/@kyle-t-jones/hpc-for-seismic-data-in-the-oil-and-gas-industry-with-aws-4b27ceae48b4](https://medium.com/@kyle-t-jones/hpc-for-seismic-data-in-the-oil-and-gas-industry-with-aws-4b27ceae48b4)

## Business context

Seismic data interpretation helps the oil and gas industry identify potential hydrocarbon reserves. Traditionally, this process has been labor-intensive and time-consuming, but advancements in high-performance computing (HPC) and cloud technologies are revolutionizing the field. AWS provides a range of HPC solutions that enhance seismic data processing, making it more efficient and cost-effective.

Interpreting 3D seismic data involves identifying geological features such as salt bodies and faults. Manual interpretation can take weeks, but AWS provides tools to automate this process. For instance, Amazon SageMaker, a fully managed service that enables data scientists to build, train, and deploy machine learning models at scale, can be used to automate horizon picking using deep learning techniques. By leveraging SageMaker and Apache MXNet, data scientists can create customized semantic-segmentation models to interpret geological features on 3D seismic data efficiently.

The seismic processing workflow is traditionally executed on on-premises HPC centers, requiring extensive IT infrastructure and significant capital investment. AWS offers on-demand seismic processing (OdSP) solutions that eliminate the need for elaborate IT planning. By utilizing GeoTomo's software --- TomoPlus and GeoThrust --- on AWS, companies can execute seismic processing jobs in a cost-managed, fully scalable, and turnkey delivered HPC environment. This approach allows for the creation of HPC clusters in the cloud as needed, scaling resources appropriately, and dissolving them upon project completion, thereby reducing costs and increasing agility.



## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).