# iat-pqos
This is an enhancement of the [Intel RDT Software Package](https://github.com/intel/intel-cmt-cat). 
It includes functionalities of monitoring and tuning DDIO behavior for better I/O performance. 

The corresponding paper, "Don't Forget the I/O When Allocating Your LLC" has appeared in [ISCA'21](https://www.iscaconf.org/isca2021/).


The DDIO monitoring functionalities have been merged to the mainstream of the official [Intel RDT Software Package](https://github.com/intel/intel-cmt-cat) (version >= 4.4.0). 
Due to some NDA issues, we are still working on open-sourcing the DDIO tuning part; meanwhile, please feel free to contact [Yifan Yuan](mailto:yifany3@illinois.edu) for early access possibility if you are interested. 


## Related Publication

```bibtex
@inproceedings {yuan-iat,
author = {Yuan, Yifan and Alian, Mohammad and Wang, Yipeng and Wang, Ren and Kurakin, Ilia and Tai, Charlie and Kim, Nam Sung},
title = {Don't Forget the {I/O} When Allocating Your {LLC}},
booktitle = {Proceedings of the 48th IEEE/ACM International Symposium on Computer Architecture (ISCA'21)},
year = {2021},
month = jul,
address = {Virtual Event}
}
```
