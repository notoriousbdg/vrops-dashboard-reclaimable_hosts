
# Reclaimable Hosts Dashboard for vRealize Operations 7.0, 7.5 and 8.0
---------

Use this [vRealize Operations](https://www.vmware.com/products/vrealize-operations.html) dashboard to identify clusters with reclaimable hosts and the potential cost savings by reclaiming the hosts.

## Dashboard
![Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/Dashboard.png)

## Installation
1. Import the super metric at `Administration` / `Configuration` / `Super Metrics` / `Import Super Metric`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/Import_Super_Metric.png)
2. Click `Browse...` then select the file named [SuperMetric - Reclaimable Hosts.json](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/raw/master/SuperMetric%20-%20Reclaimable%20Hosts.json)
3. Edit the Policy at `Administration` / `Policies` / `Policy Library`.  The policy should be `vSphere Solution's Default Policy (DATE)` unless a new policy was explicitly created.  
![Policy Library](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/Policy_Library.png)
4. Enable all Super Metrics on Cluster Compute Resource objects that start with `Super Metric|Reclaimable Hosts`.  
![Policy Metrics](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/Policy_Metrics.png)
5. Import the view at `Dashboards` / `Views` / `Import...`  
![Import View](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/Import_View.png)
6. Click `Browse...` then select the file named [Views - Reclaimable Hosts.zip](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/raw/master/Views%20-%20Reclaimable%20Hosts.zip)
7. Import the dashboard at `Dashboards` / `Actions` / `Manage Dashboards` / `Import Dashboards`  
![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/Import_Dashboard.png)
8. Click `Browse...` then select the file named [Dashboard - Reclaimable Hosts.zip](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/raw/master/Dashboard%20-%20Reclaimable%20Hosts.zip)
9. The dashboard should now be available in in the dashboard list  
![Dashboard List](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/master/Dashboard_List.png)

## Support

This dashboard requires vRealize Operation 7.0, 7.5, or 8.0 Advanced or Enterprise edition.

Please open an [issue](https://github.com/notoriousbdg/vrops-dashboard-reclaimable_hosts/issues) for feedback.
