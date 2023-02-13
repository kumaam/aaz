# [Command] _network vnet-gateway root-cert delete_

Delete a root certificate.

## Versions

### [2022-01-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL3ZpcnR1YWxuZXR3b3JrZ2F0ZXdheXMve30=/2022-01-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/virtualnetworkgateways/{} 2022-01-01 properties.vpnClientConfiguration.vpnClientRootCertificates[] -->

#### examples

- Remove a certificate from the list of Root Certificates whose children are allowed to access this Gateway.
    ```bash
        network vnet-gateway root-cert delete -g MyResourceGroup -n MyRootCertificate --gateway-name MyVnetGateway
    ```

- Delete a root certificate.
    ```bash
        network vnet-gateway root-cert delete --gateway-name MyVnetGateway --name MyRootCertificate --resource-group MyResourceGroup --subscription MySubscription
    ```