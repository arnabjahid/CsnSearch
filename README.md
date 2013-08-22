CsnSearch
=======

**What is CsnSearch?**

CsnSearch is a Module based on Zend Framework 2


Installation
============

Installation via composer is supported, simply add the following line to your ```composer.json```

```
"repositories": [
	{
		"type": "vcs",
		"url": "https://github.com/coolcsn/CsnSearch"
	}
],
"require" : {
    "coolcsn/csn-search": "dev-master"
}
```

After adding to the composer's packagist.org (not ready yet)

```
"require" : {
    "coolcsn/csn-search": "dev-master"
}
```
Run ```php composer.phar update```

Go to your application configuration in ```./config/application.config.php```and add 'CsnSearch'.
An example application configuration could look like the following:

```
'modules' => array(
    'Application',
	'CsnSearch',
)
```


Recommends
==========
- [coolcsn/CsnUser] (https://github.com/coolcsn/CsnUser) - Authentication (login, registration) module, fully compatible with CsnAuthorization.

- [coolcsn/CsnAuthorization](https://github.com/coolcsn/CsnAuthorization) - Authorization fully compatible with CsnUser;

- [coolcsn/CsnAclNavigation] (https://github.com/coolcsn/CsnAclNavigation) - Navigation using Access Control List;

- [coolcsn/CsnCms](https://github.com/coolcsn/CsnCms) - Content management system;
