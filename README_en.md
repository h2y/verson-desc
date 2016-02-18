# Standard for Verson-name By.Moshel

[点击查看中文版本](https://github.com/h2y/verson-desc/blob/master/README.md)

Document verson：__v0.1.0.1-en__

Last modify date：__16-02-18__


## CONTENTS
This standard will be used in most of my projects. It refer to
[Semantic Versioning](http://semver.org/)'s basic ideas, meanwhile,
it has lots of particular features.

> **Verson Format :**
>
> `MAJOR . MINOR . PATCH . COUNTS [ -INFO ]`
>
> **Examples :**
>
> v0.12.1.13
>
> v1.0.1.15
>
> v2.0.0.16-beta

### Major
I made incompatible API changes in this verson, or changed the basic framework
and designs.

If the Major verson is 0, seems the projects is in devoloping, and it maybe
changes fast at that time.

Because of the incompatible changes, users should be careful to update.

### Minor
Update in a backwards-compatible manner. Project always add some new function
at that time.

### Patch
No new functions, but I make some bug fixes or optimize at that time.

### Counts
The number is 0 at first, and add 1 in each new verson.

Through the number, users could obtain how may generations between the current
verson and the lastest verson.

### Info
Option. Use - symbol to connect with other items in the end. Don't be used to
judge in versons, just wrote for hunman. And no stationary formats, only some
words I want to say.

For Example, _-beta、-alpha_ seem it's a verson for test.

_-must_ seems I suggest you updating right now.


************
## RELATED ITEMS

* **First Verson**

  The first verson to four number is 0. So, the first verson is v0.0.0.0, and
the first stable verson is v1.0.0.x.

* **Carry Rules for Verson Number**

  In addition to the last Counts number , the remaining three version numbers
using decimal. For example, it will update to v1.3.0.65 after v1.2.9.64 even if
there are only some bug fixes. That is, there is no version such as v1.2.10.65.

  Is not the 10 smaller updates can not be seen as a major update? Besides, the
most important reason is the smaller version number is more readable and it's
easy to remember for us.

* **Updating Frequency**

  Users worry about the verson number increase soo quickly. To deal with the
problem, I made the standard of the frequency at there.

  1. Make patch update verson only once in a day, if there are more than
one times, merge them.
  2. Update the Minor version number only once a week.
  3. Major version number update cycle for several months, or longer.
  4. If a serious bug appear, repaire it immediately, without any of the above
restrictions.

* **Permanent Link for This Page**

  This document is maintained by Github. Welcome everyone to submit Issues and
share your views.

  Permanent link: <https://github.com/h2y/verson-desc/blob/master/README_en.md>
