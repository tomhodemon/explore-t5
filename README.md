# explore-t5

> [!NOTE]
> This repository is based off the [nanoT5](https://github.com/PiotrNawrot/nanoT5) repository, see [LICENSE](nanoT5/LICENSE).

## WIP

- [x] Add a layer of abstraction to T5Block to implement SharedEnc, SharedDec & SharedEncSharedDec
- [ ] TensorBoard support
- [ ] Running experiments
- [ ] Clean up repository

## Configurations & support

We use the same nomenclature as presented in the original [T5 paper](https://arxiv.org/pdf/2309.01826.pdf).

<div align="left">

| **Model** | **Configuration** | **Num. of parameters** | **Support** |
| :----: | :---- | :---: | :---: |
| `google/t5-v1_1-small` | Vanilla | Nd. | :white_check_mark: |
| `google/t5-v1_1-small` | SharedEnc | Nd. | :white_check_mark: |
| `google/t5-v1_1-small` | SharedDec | Nd. | :white_check_mark: |
| `google/t5-v1_1-small` | SharedEncSharedDec | Nd. | :white_check_mark: |
| `google/t5-v1_1-small` | SharedEncDec | Nd. | :x: |
| `google/t5-v1_1-small` | NoDec | Nd. | :x: |
| `google/t5-v1_1-small` | SharedEncNoDec | Nd. | :x: |

</div>

## Experimentation results

<div align="left">

| **Model** | **Configuration** |
| :----: | :---- |
| `google/t5-v1_1-small` | Vanilla |
| `google/t5-v1_1-small` | SharedEnc |
| `google/t5-v1_1-small` | SharedDec |
| `google/t5-v1_1-small` | SharedEncSharedDec |
| `google/t5-v1_1-small` | SharedEncDec |
| `google/t5-v1_1-small` | NoDec |
| `google/t5-v1_1-small` | SharedEncNoDec |

</div>