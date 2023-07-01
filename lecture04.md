# 第4回課題
## VPCの作成
- AWS上にVPCが作成されていることを確認。
![VPC作成確認](./image/lecture04_01_vpc.png)
![VPC作成確認](./image/lecture04_02_vpc.png)

## EC2の構築
- 作成したVPC上にEC2が構築されていることを確認。
![EC2構築確認](./image/lecture04_03_EC2.png)
- EC2のセキュリティグループを確認。
![EC2セキュリティグループ確認](./image/lecture04_04_EC2.png)
![EC2セキュリティグループ確認](./image/lecture04_05_EC2_ver02.png)

## RDSの構築
- 作成したVPC上にRDSが構築されていることを確認。
![RDS構築確認](./image/lecture04_06_RDS.png)
- RDSのセキュリティグループを確認。
![RDSセキュリティグループ確認](./image/lecture04_07_RDS_ver02.png)

## EC2からRDSに接続する
- 接続が正常にできることを確認。
![接続確認](./image/lecture04_08_mysql_ver02.png)

## その他の操作
- 接続確認後、EC2のセキュリティグループのソースが0.0.0.0/0となっており、セキュリティに問題があったためホストのIPアドレスへ変更した。
- RDSのセキュリティグループのソースも本来意図していたものとは違ったため、EC2インスタンスのIPアドレスへ変更した。

