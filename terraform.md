# Установка Terraform

Скачиваем с https://hashicorp-releases.yandexcloud.net/terraform
Если установку выполняете из терминала linux то качаем так:

```
wget https://hashicorp-releases.yandexcloud.net/terraform/1.6.4/terraform_1.6.4_linux_amd64.zip
```
Рапаковываем программой  unzip
```
 unzip terraform_1.6.4_linux_amd64.zip
```
Копмруем файл terraform в  /usr/local/bin/ 
```
mv terraform /usr/local/bin/
```
Проверяем
```
terraform -version
```
Ответ версия программы, значит все работает.
![](https://user-images.githubusercontent.com/136073445/284554563-4589ad0e-1ac6-47b2-aad1-4fb54fe2dced.png)

