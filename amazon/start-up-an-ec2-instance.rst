Start up an EC2 instance
========================

Log in
~~~~~~

Go to 'https://aws.amazon.com' in a Web browser.

Select 'My Account/Console' menu option 'AWS Management Console."

Log in with your username & password.

Click on EC2 (upper left).

.. image:: images/ec2-1.png
   :width: 80%

Select your zone
~~~~~~~~~~~~~~~~

Many of the resources that we use are hosted by Amazon on the East coast.
Make sure that your dashboard has 'N. Virginia' on the upper right.

Then click on Launch Instance.

.. image:: images/ec2-2.png
   :width: 80%

Select the machine operating system to boot
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Choose 'Community AMIs', enter 'beacon' into the search box, and
click on 'Select'.

.. image:: images/ec2-3.png
   :width: 80%

Choose the machine size
~~~~~~~~~~~~~~~~~~~~~~~

Select 'General purpose', 'm1.xlarge', and then 'Review and Launch'.

Enter 'ami-7f340c16' into the search box and click "search".  Select
it, and hit Continue.

.. image:: images/ec2-4.png
   :width: 80%

Confirm and launch
~~~~~~~~~~~~~~~~~~

Review the details (ignore the warnings!) and click on Launch.

.. image:: images/ec2-5.png
   :width: 80%

(First time through) generate a new key pair
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you don't have any key pairs, enter a key pair name and
then download a key pair.  Then click Launch Instance.

.. image:: images/ec2-6.png
   :width: 80%

(Next times through) select an existing key pair
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Select a key pair and click 'Launch'.

.. image:: images/ec2-7.png
   :width: 80%

Click on View Instances
~~~~~~~~~~~~~~~~~~~~~~~

.. image:: images/ec2-8.png
   :width: 80%

Select the public DNS name for later use
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: images/ec2-9.png
   :width: 80%
