# Configure a Linux server on AWS

If you do not have access to a computer running Linux \(or VirtualBox\), you can use Amazon Web Services \(AWS\) to create a cloud-based virtual machine running Linux for free. To do so, please follow the steps below:

* Go to [Amazon Web Services \(AWS\)](https://aws.amazon.com/) and create a \(free\) account if you do not have one already.
* Go to the _AWS Management Console_.
* Go to the _EC2 Dashboard_.

![AWS Management Console.](images/AMI.png)

* If you already have a running instance, go to step 9.
* We first make sure to get enough harddrive space \(at least 24GB\). Click on _Volumes_.

![Volumes in the Management Console.](https://github.com/cardano-foundation/stake-pool-school-handbook/tree/490a2c877b1c2b93450333a8297d1c398b950536/.gitbook/assets/volumes.png)

* Under _Actions_, select _Modify Volume_.

![Volume Actions.](https://github.com/cardano-foundation/stake-pool-school-handbook/tree/490a2c877b1c2b93450333a8297d1c398b950536/.gitbook/assets/volume_actions.png)

* In the _Modify Volume_ diaglog, select a size of 24 and click _Modify_, then confirm in the next dialog.

![Modify Volume.](https://github.com/cardano-foundation/stake-pool-school-handbook/tree/490a2c877b1c2b93450333a8297d1c398b950536/.gitbook/assets/modify_volume.png)

* Go back to the _EC2 Dashboard_.

![EC2 Dashboard.](https://github.com/cardano-foundation/stake-pool-school-handbook/tree/490a2c877b1c2b93450333a8297d1c398b950536/.gitbook/assets/dashboard.png)

* Go to _Launch Instance_.

![Launch Instance.](https://github.com/cardano-foundation/stake-pool-school-handbook/tree/490a2c877b1c2b93450333a8297d1c398b950536/.gitbook/assets/launch_instance.png)

* As Amazon Machine Image, choose _Amazon Linux 2 \(HVM\), SSD Volume Type_, 64-bit \(x86\).

![Amazon Machine Image.](https://github.com/cardano-foundation/stake-pool-school-handbook/tree/490a2c877b1c2b93450333a8297d1c398b950536/.gitbook/assets/AMI.png)

* As Instance Type, choose _t2.medium_, then click _Review and Launch_ and finally _Launch_ on the next screen.

![Instance Type.](https://github.com/cardano-foundation/stake-pool-school-handbook/tree/490a2c877b1c2b93450333a8297d1c398b950536/.gitbook/assets/Instance_Type.png)

* Create a key pair \(or use an existing one\).

![Create a key pair.](https://github.com/cardano-foundation/stake-pool-school-handbook/tree/490a2c877b1c2b93450333a8297d1c398b950536/.gitbook/assets/key_pair.png)

* _Connect_ to your instance.

![Connect.](https://github.com/cardano-foundation/stake-pool-school-handbook/tree/490a2c877b1c2b93450333a8297d1c398b950536/.gitbook/assets/connect.png)

* You can use the _EC2 Instance Connect_ connection method.

![Choose connection method.](https://github.com/cardano-foundation/stake-pool-school-handbook/tree/490a2c877b1c2b93450333a8297d1c398b950536/.gitbook/assets/connect2.png)





{% hint style="info" %}
[QUESTIONS AND FEEDBACK](https://github.com/carloslodelar/SPO/issues)

If you have any questions or need help, please raise an issue in [Github.](https://github.com/cardano-foundation/stake-pool-school-handbook/issues) We will respond as soon as possible.
{% endhint %}

Congratulations! You have now access to a machine running Linux.
