custodian run --output-dir ouput --region us-east-2 running-instances.yaml
custodian report --output-dir ouput --region us-east-2 running-instances.yaml

#  docker build -t arturcorreiajunior/cloud-custodian-aws:latest .  && docker push  arturcorreiajunior/cloud-custodian-aws:latest
#  docker run -d -p 8080:80 arturcorreiajunior/cloud-custodian-aws:latest