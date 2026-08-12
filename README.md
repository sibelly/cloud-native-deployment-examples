# Exemplos usados na demonstração da talk

[Slides](https://docs.google.com/presentation/d/18bHT_kW2bx_kLBFqpBLuqzlVUUoI9RXreCrnmqKm2Fk/edit?usp=sharing)

## Istio
[link](https://istio.io/latest/docs/setup/getting-started/)
```
curl -L https://istio.io/downloadIstio | sh -
cd istio-1.30.3
export PATH=$PWD/bin:$PATH
```

```
istioctl install --set profile=ambient --skip-confirmation
```

## Argo Rollouts
[link](https://argo-rollouts.readthedocs.io/en/stable/)
```
kubectl create namespace argo-rollouts
kubectl apply -n argo-rollouts -f https://github.com/argoproj/argo-rollouts/releases/latest/download/install.yaml
```