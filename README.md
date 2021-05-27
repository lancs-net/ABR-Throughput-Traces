# ABR-Throughput-Traces

This dataset contains 7,000 throughput traces, with the mean throughput of 3261 kbps and duration of 4 minutes.

The traces were calculated from CDN logs of a live HTTP Adaptive Streaming (HAS) service, BT Sport 1, which offers live sports content.

CDN logs included data from a single day in 2018.

The data was filtered to only include traces were the mean throughput is less than 4800 kbps, resulting in 7,000 traces.

The distribution of throughput measurements in this dataset is shown below.

![histogram](https://user-images.githubusercontent.com/16705289/119779411-92c03380-bec0-11eb-9499-c84e8d10b2fb.png)

This dataset was used in the following papers:

```
@inproceedings{lyko2020llama,
  title={Llama-Low Latency Adaptive Media Algorithm},
  author={Lyko, Tomasz and Broadbent, Matthew and Race, Nicholas and Nilsson, Mike and Farrow, Paul and Appleby, Steve},
  booktitle={2020 IEEE International Symposium on Multimedia (ISM)},
  pages={113--121},
  year={2020},
  organization={IEEE}
}
@inproceedings{lyko2020evaluation,
  title={Evaluation of CMAF in live streaming scenarios},
  author={Lyko, Tomasz and Broadbent, Matthew and Race, Nicholas and Nilsson, Mike and Farrow, Paul and Appleby, Steve},
  booktitle={Proceedings of the 30th ACM Workshop on Network and Operating Systems Support for Digital Audio and Video},
  pages={21--26},
  year={2020}
}
```

If you use this dataset in your research, please reference the top paper from above.
Please do not redistribute this dataset and instead link to this repository directly.
 
