
# Reclaimable Hosts Dashboard for vRealize Operations 7.0, 7.5, 8.0, 8.1, 8.2, and Cloud
---------

Use this [vRealize Operations](https://www.vmware.com/products/vrealize-operations.html) dashboard to identify clusters with reclaimable hosts and the potential cost savings by reclaiming the hosts.

## Dashboard
![Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/images/Dashboard.png)

## Installation
1. Import the super metrics at `Administration` / `Configuration` / `Super Metrics` / `Import Super Metric`  
![Import Super Metric](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/images/Supermetric_Import.png)
2. Click `Browse...` then select the file named [supermetric.json](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/supermetric.json)
3. For each Super Metric listed in the [Super Metrics section](#Super-Metrics), click on the vertical kebab and select edit.  
![Policy Metrics](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/images/Supermetric_Edit.png)
4. Enable the Super Metric for each Policy shown in the `Enable in a Policy` stage of the wizard.
![Policy Library](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/images/Supermetric_Policy.png)
5. Repeat the previous 2 steps for the remaining Super Metrics listed in the [Super Metrics section](#Super-Metrics).
6. Import the view at `Dashboards` / `Views` / `Import...`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/images/View_Import.png)
7. Click `Browse...` then select the file named [Views.zip](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/raw/master/Views.zip)
8. The included views are listed in the [Views section](#Views)
9. Import the dashboard at `Dashboards` / `Actions` / `Manage Dashboards` / `Import Dashboards`  
![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/images/Dashboard_Import.png)
10. Click `Browse...` then select the file named [Dashboard.zip](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/raw/master/Dashboard.zip)
11. The dashboard should now be available in in the dashboard list  
![Dashboard List](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/images/Dashboard_List.png)
12. The included dashboards are listed in the [Dashboards section](#Dashboards)

## Dashboards
| Dashboard Name | Dashboard Path |
|--|--|
| Reclaimable Hosts | Shared Dashboards (GBrandon)/Cost |

## Views
| View Name | Name on Dashboard | View Type |
|--|--|--|
| Reclaimable Hosts Pie Chart | Reclaimable Hosts Cost Pie Chart | Distribution |
| Reclaimable Hosts Detail | Reclaimable Hosts Detail | List |

## Super Metrics
| Super Metric Name | Object Type |
|--|--|
| Number of Reclaimable Hosts | vSphere World |
| Number of Reclaimable Hosts | Custom Datacenter |
| Number of Reclaimable Hosts | Datacenter |
| Potential Savings from Reclaimable Hosts | vSphere World |
| Potential Savings from Reclaimable Hosts | Custom Datacenter |
| Potential Savings from Reclaimable Hosts | Datacenter |
| Reclaimable Hosts | Cluster Compute Resource |
| Reclaimable Hosts by CPU | Cluster Compute Resource |
| Reclaimable Hosts by Memory | Cluster Compute Resource |
| Reclaimable Hosts Cost | Cluster Compute Resource |
| Reclaimable Hosts Cost by CPU | Cluster Compute Resource |
| Reclaimable Hosts Cost by Memory | Cluster Compute Resource |

## Support

This dashboard requires vRealize Operation 7.0, 7.5, 8.0, 8.1, or 8.2 Advanced or Enterprise edition or vRealize Operations Cloud.

Please open an [issue](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/issues) for feedback.

## Changelog
2018-11-19
* Initial release

2019-04-30
* Update for vRealize Operations 7.5

2019-10-24
* Update for vRealize Operations 8.0

2020-05-13
* Update for vRealize Operations 8.1
* Update readme format
* Added summary rollup metrics for datacenter, custom datacenter, and vSphere World
* Added Potential Savings chart
