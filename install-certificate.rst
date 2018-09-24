Install Certificate on the Server
****************************

You should have received the certificate package after setting up the plugin and requesting SSL. Download the attachment in the email and extract it. You will get 3 files,

* your_site_domain.crt
* your_site_domain.key
* chain.crt

Now, let's install the certificate on the server. Take cPanel as the example. Go to cPanel --> **SSL/TLS**.

.. image:: /images/04_cPanel.png

On the page, choose **Manage SSL Sites.**

.. image:: /images/05_Install_SSL.png

Here, you can install the new certificate easily. Choose the domain first and them copy/paste the codes in the certificate files to the corresponding fields.

* your_site_domain.crt --> Certificate: (CRT)
* your_site_domain.key --> Private Key (KEY)
* chain.crt --> Certificate Authority Bundle: (CABUNDLE)

.. image:: /images/06_Copy_Codes.png

Click button **Install Certificate** and you will get the success message. The certificate is successfully installed now.

.. image:: /images/07_Success_Message.png