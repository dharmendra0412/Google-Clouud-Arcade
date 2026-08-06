 Run in Cloud Shell:

```bash
export ZONE=$(gcloud compute project-info describe \
--format="value(commonInstanceMetadata.items[google-compute-default-zone])")
gcloud compute ssh centos-clean --zone=$ZONE --quiet
```


```bash
curl -LO https://raw.githubusercontent.com/dharmendra0412/Google-Clouud-Arcade/refs/heads/main/Configuring%20IAM%20Permissions%20with%20gcloud/dharmendra.sh
sudo chmod +x dharmendra.sh 
./dharmendra.sh
```
