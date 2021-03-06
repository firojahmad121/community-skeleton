<p align="center"><a href="https://www.uvdesk.com/en/" target="_blank">
    <img src="https://s3-ap-southeast-1.amazonaws.com/cdn.uvdesk.com/uvdesk/bundles/webkuldefault/images/uvdesk-wide.svg">
</a></p>

A fully-functional [UVDesk Community Edition][1] project skeleton packaged along with the bare essential utilities that you can use to develop your own custom helpdesk solutions.

Click [here][2] to view the live community project demo.

What's Included?
--------------

The standard distribution comes pre-configured with the following bundles:

  * [**UVDeskCoreBundle**][3] - The core framework bundle for bulding helpdesk solutions

  * [**UVDeskAutomationBundle**][4] - Adds support for workflows and prepared responses to automate any specific operations within your helpdesk system

  * [**UVDeskSupportCenterBundle**][5] - Integrates the easily customizable support center portal to enable users to easily interact with the support staff through your helpdesk system

Installation
--------------

Before creating your UVDesk Community project, make sure that you're using PHP 7 or higher and have [Composer][6] installed. You also need to ensure that you have the following PHP extensions installed:

  * [PHP IMAP][7]
  * [PHP Mailparse][8]

To create your project, run the following command:

```bash
$ composer create-project uvdesk/community-skeleton:^0.1-dev helpdesk-project
```

About Us
--------------
The development of the UVDesk Community Edition is supported by [Webkul][9], led by the [UVDesk Team][10].

Visit our official [website][1] to learn more about the UVDesk Helpdesk System.

License
--------------

All libraries and bundles included in the UVDesk Community Edition are released under the MIT or BSD license.

[1]: https://www.uvdesk.com/
[2]: https://community.uvdesk.com/en/
[3]: https://github.com/akshaywebkul/core
[4]: https://github.com/akshaywebkul/automations
[5]: https://github.com/akshaywebkul/support-center
[6]: http://php.net/manual/en/book.imap.php
[7]: http://php.net/manual/en/book.mailparse.php
[8]: https://getcomposer.org/
[9]: https://webkul.com/
[10]: https://www.uvdesk.com/en/team/
