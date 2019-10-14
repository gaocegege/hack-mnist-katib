## 单机 MNIST

仅供 [kubeflow/katib](https://github.com/kubeflow/katib) 进行测试用。

### 镜像

gaocegege/tensorflow-mnist-example:1.14.0-with-summaries

## 分布式 MNIST

仅供 [kubeflow/katib](https://github.com/kubeflow/katib) 进行测试用。

### 镜像

gaocegege/tf-dist-mnist-test:1.2

每次训练会输出 validation cross entropy：

```
1565943718.328076: Worker 0: training step 492 done (global step: 981)
1565943718.328076 entropy=905.217
1565943718.510096: Worker 0: training step 493 done (global step: 984)
1565943718.510096 entropy=973.543
1565943718.626882: Worker 0: training step 494 done (global step: 985)
1565943718.626882 entropy=1018.24
1565943718.776797: Worker 0: training step 495 done (global step: 988)
1565943718.776797 entropy=911.474
1565943718.934602: Worker 0: training step 496 done (global step: 990)
1565943718.934602 entropy=864.287
1565943719.063167: Worker 0: training step 497 done (global step: 992)
1565943719.063167 entropy=872.495
1565943719.232702: Worker 0: training step 498 done (global step: 994)
1565943719.232702 entropy=865.085
1565943719.382063: Worker 0: training step 499 done (global step: 997)
1565943719.382063 entropy=880.084
1565943719.511230: Worker 0: training step 500 done (global step: 999)
1565943719.511230 entropy=859.146
1565943719.676318: Worker 0: training step 501 done (global step: 1001)
1565943719.676318 entropy=847.719
Training ends @ 1565943719.771756
Training elapsed time: 105.401720 s
After 1000 training step(s), validation cross entropy = 847.719
```