---
id: quickstart
title: Quickstart Guide to OpenEBS
sidebar_label: Quickstart
---
------

<br>

<a href="/docs/next/prerequisites.html"><img src="/docs/assets/svg/config-sequence.svg" alt="OpenEBS configuration flow" style="width:100%"></a>



<br>

<font size="5">Steps:</font>



<div class="emphasize">
    <ul>
        <li>Kubernetes 1.13+ installed. Latest tested Kubernetes version is 1.16.1.</li>
        <li>For using features like Local PV and Backup & Restore, you must require Kubernetes version 1.13 or above.
        </li>
        <li>For provisioning cStor volume via CSI driver support and performing basic operations on this volume such as expanding volume and snapshot & clone, you must require Kubernetes version 1.14 or above</li>
        <li>Understand the <a href="/v160/docs/next/prerequisites.html">pre-requisites</a> for your Kubernetes platform</li>
        <li>Start <a href="/v160/docs/next/installation.html">installation </a> through OpenEBS operator.</li>
        <li>For production deployments or to test OpenEBS volumes on real disks, create cStorPools, cStor-StorageClasses and start provisioning volumes using the newly created cStor-StorageClasses. More details can be find from <a href="/v160/docs/next/ugcstor.html">here.</a></li>
        <li>For high performance required applications which manage their own replication, data protection and other storage features, provision OpenEBS Local PV. More details can be find from <a href="/v160/docs/next/uglocalpv.html">here.</a></li>
    </ul>









</div>





<br>

<font size="5">As a first step, follow the instructions to setup or verify iSCSI clients on any of the platforms below </font>

<div class="emphasize">
[Ubuntu](/v160/docs/next/prerequisites.html#ubuntu)

[RHEL](/v160/docs/next/prerequisites.html#rhel)

[CentOS](/v160/docs/next/prerequisites.html#centos)

[OpenShift](/v160/docs/next/prerequisites.html#openshift)

[Rancher](/v160/docs/next/prerequisites.html#rancher)

[ICP](/v160/docs/next/prerequisites.html#icp)

[EKS](/v160/docs/next/prerequisites.html#eks)

[GKE](/v160/docs/next/prerequisites.html#gke)

[AKS](/v160/docs/next/prerequisites.html#aks)

[Digital Ocean](/v160/docs/next/prerequisites.html#do)

[Konvoy](/v160/docs/next/prerequisites.html#konvoy)

<br>

</div>



[Provide feedback](https://github.com/openebs/openebs-docs/edit/staging/docs/quickstart.md) if a platform is missing in the above list

<br>

<hr>

<br>

