# Helm Chart To Deploy Backend Apps

## Requirements

- 4GB Ram
- 2 cpu
- 40GB Storage

## Create a secret 
```
kubectl create secret docker-registry harbor-registry-secret \
  --docker-server=harbor.staging.ignite.dev \
  --docker-username=your-username \
  --docker-password=your-password \
  --docker-email=your-email@example.com

```
## To deploy nodejs
```
kubectl install nodejs . --values=nodejs-values.yaml
```

## To deploy Laravel
```
kubectl install laraavel . --values=laravel-values.yaml
```

## To deploy Django
```
kubectl install django . --values=django-values.yaml
```

## To deploy Dotnet
```
kubectl install dotnet . --values=dotnet-values.yaml
```


## To deploy Flask
```
kubectl install flask . --values=flask-values.yaml
```

## To deploy Ruby on Rails
```
kubectl install ruby-on-rails . --values=ruby-on-rails-values.yaml
```

## To deploy Spring Boot
```
kubectl install springboot . --values=springboot-values-values.yaml
```

## To deploy Nextjs
```
kubectl install nextjs . --values=nextjs-values-values.yaml
```

## To deploy Java(Play Framework)
```
kubectl install java-play-framework . --values=java-playframework-values.yaml
```

## To deploy Rust
```
kubectl install rust . --values=rust-values.yaml
```