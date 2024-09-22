# HHA504_assignment_networking
The objective of this assignment is to explore the networking features in Azure and Google Cloud Platform (GCP), focusing on Virtual Private Cloud (VPC), Virtual Private Network (VPN), IP addresses, and domain management. You will gain practical experience in assigning dedicated IPs and mapping them to domains.
# 1. Create a Virtual Private Cloud (VPC)
### *Azure*
![Azure vnet](https://github.com/user-attachments/assets/fa8e1932-1580-4746-ae58-d061eee52b92)
### *GCP*
![GCP vpc](https://github.com/user-attachments/assets/fbd3597d-9496-4a6e-bf30-cfb1e47a666d)

# 2. Assign a Dedicated IP
### *Azure*
![Azure dedicated IP](https://github.com/user-attachments/assets/b70d7fbb-3d1c-4bad-8571-6f74e64d796f)
### *GCP*
![GCP dedicated IP](https://github.com/user-attachments/assets/523ecb34-94f2-4014-97b4-6d6e644d1e93)

# 3. Map IP to a Domain
### *Azure*
![Azure map IP](https://github.com/user-attachments/assets/bd295f1f-70f4-4da9-b435-fd18dc42e6cf)
### *GCP*
![GCP map IP](https://github.com/user-attachments/assets/e3bc51a8-6325-4bca-9ebe-6bee41ff44aa)

# 4. Explore VPN and Tunnels 
### *Azure*
  1. Set up VNet
  2. Select "Create a resource" and select "Virtual network gateway"
  3. Enter name of VPN gateway, region, type of gateway, VPN type, SKU, vitural network, and public      IP address
  4.Click review + create
  5. Create local network by selecting "local network gateway" under "create resource"
  6. Enter name, IP address, and address space
  7. Click review + create
  8. Select resource group for VPN gateway and select the VPN gateway that was created
  9. Select "connections" under "settings" and click on "+ Add"
  10. Enter name, connection type, local network gateway, shared key
  11. Click "OK"
  12. To set up tunnel use public IP address of VPN gateway and shared key
  13. Update firewall by allowing traffic from the VNet that was created
### *GCP*
  1. Create gateway by clicking create VPN
  2. Enter name of VPN gateway, select region, choose network for VPC
  3. Create VPN tunnel by clicking create tunnel
  4. Enter name for tunnel, IKE version, shared secret authentication, and type of IP address
  5. Update firewall rules to allow traffic by allowing IP ranges 
