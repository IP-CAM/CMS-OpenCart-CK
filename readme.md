# CloudKassir Module for OpenCart

The module allows you to integrate the online cashier [CloudKassir] (https://cloudkassir.ru/) to the online store on the OpenCart platform.

### Opportunities
* Automatic sending arrival checks;
* Sending arrival check checks;
* Separate VAT setting for delivery services;
* Sending checks to the email client;
* Sending checks in SMS;

### compatibility
* OpenCart v.3.0 and above;
### Installation through the control panel

In the Administrator panel, go to the "Modules / Extensions" section -> "Install Extensions" and upload an archive.

### Manual Installation

Unpack from the archive Upload directory and download to the root of OpenCart.

### Setting up module

1. Go to the "Modules / Expansion" module settings -> "Modules / Extensions" -> "Modules".
Select CloudKassir and activate the module.
2. Go to the module settings and specify:
    * Site Identifier - Public Website ID from Personal Cabinet CloudPayments
    * Secret key - SECRET API from Personal Cabinet CloudPayments
    * INN INN of the Organization to which online cash register
    * Status - Included
    * VAT rate - indication of VAT rates.
        All possible values ​​are indicated in the documentation https://cloudpayments.ru/docs/Kassa#Data-Format
    * VAT rate for delivery - specifying a separate VAT rate for delivery.
        If shipping is paid, then it is drawn up in the check with a separate line with its VAT rate.
        Values ​​are similar to VAT rate for goods.
    * Taxation system - type of taxation system.
        Possible values ​​are listed in the documentation CloudPayments https://cloudpayments.ru/docs/directory#Taxation-System
    * Payment statuses for payment - Choosing an order status, with transportation to which a request for generating an online arrival check is sent. Default "Waiting"
    * Reference order statuses - Choosing an order status, with a transport of which is sent to generate an online return check. By default, "Cancel and Anulating"

    Then save the entered parameters.
    
