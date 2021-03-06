# Template mod_login [16/41]
* [Chemin](#chemin)
* [Description](#description)
* [Variables disponibles](#variables-disponibles)
* [Template par défaut PunBB](#template-par-dfaut-punbb)
* [Template par défaut phpBB2](#template-par-dfaut-phpbb2)

## Chemin
[`Index`](http://votre-forum.appspot.com/#/admin/,&part=themes,&mode=portal&sub=templates,?mode=edit_portal&part=themes&sub=templates&t=916) > [`Panneau d'administration`](http://votre-forum.appspot.com/admin/#&part=themes,&mode=portal&sub=templates,?mode=edit_portal&part=themes&sub=templates&t=916) > [`Affichage`](http://votre-forum.appspot.com/admin/?part=themes#&mode=portal&sub=templates,?mode=edit_portal&part=themes&sub=templates&t=916) > [`Templates | Portail`](http://votre-forum.appspot.com/admin/?mode=portal&part=themes&sub=templates#?mode=edit_portal&part=themes&sub=templates&t=916) > [`mod_login`](http://votre-forum.appspot.com/admin/?mode=edit_portal&part=themes&sub=templates&t=916)

## Description
[*Ajouter une description*](https://fa-tvars.appspot.com/tpl/mod_login)

## Variables disponibles
* [__Variables globales__](../../variables_globales.md#readme)
* __Variables propres à ce template :__
    * [`{AUTOLOGIN_CHECKED}`](https://github.com/Etana/template/blob/master/var/AUTOLOGIN_CHECKED.md#readme)
    * [`{DIRECTION}`](https://github.com/Etana/template/blob/master/var/DIRECTION.md#readme)
    * [`{L_MESSAGES}`](https://github.com/Etana/template/blob/master/var/L_MESSAGES.md#readme)
    * [`{L_MY_PROFILE}`](https://github.com/Etana/template/blob/master/var/L_MY_PROFILE.md#readme)
    * [`{L_PM}`](https://github.com/Etana/template/blob/master/var/L_PM.md#readme)
    * [`{L_SEND_PASSWORD}`](https://github.com/Etana/template/blob/master/var/L_SEND_PASSWORD.md#readme)
    * [`{NB_MESSAGES}`](https://github.com/Etana/template/blob/master/var/NB_MESSAGES.md#readme)
    * [`{NB_PM_READ}`](https://github.com/Etana/template/blob/master/var/NB_PM_READ.md#readme)
    * [`{NB_PM_UNREAD}`](https://github.com/Etana/template/blob/master/var/NB_PM_UNREAD.md#readme)
    * [`{USERNAME}`](https://github.com/Etana/template/blob/master/var/USERNAME.md#readme)
    * [`{USERNAME_AVATAR}`](https://github.com/Etana/template/blob/master/var/USERNAME_AVATAR.md#readme)
    * [`{U_SEND_PASSWORD}`](https://github.com/Etana/template/blob/master/var/U_SEND_PASSWORD.md#readme)
    * [`<!-- BEGIN switch_login -->...<!-- END switch_login -->`](https://github.com/Etana/template/blob/master/var/switch_login.md#readme)
    * [`<!-- BEGIN switch_login_small -->...<!-- END switch_login_small -->`](https://github.com/Etana/template/blob/master/var/switch_login_small.md#readme)
    * [`<!-- BEGIN switch_profile -->...<!-- END switch_profile -->`](https://github.com/Etana/template/blob/master/var/switch_profile.md#readme)

## Template par défaut PunBB

[__Code source__](../src/punbb/mod_login.tpl#files)

### Positions des variables 

* __[`{AUTOLOGIN_CHECKED}`](https://github.com/Etana/template/blob/master/var/AUTOLOGIN_CHECKED.md#readme) :__ lignes [`17`](../src/punbb/mod_login.tpl#L17), [`37`](../src/punbb/mod_login.tpl#L37)
* __[`{L_AUTO_LOGIN}`](https://github.com/Etana/template/blob/master/var/L_AUTO_LOGIN.md#readme) :__ lignes [`17`](../src/punbb/mod_login.tpl#L17), [`37`](../src/punbb/mod_login.tpl#L37)
* __[`{L_LOGIN}`](https://github.com/Etana/template/blob/master/var/L_LOGIN.md#readme) :__ lignes [`3`](../src/punbb/mod_login.tpl#L3), [`20`](../src/punbb/mod_login.tpl#L20), [`28`](../src/punbb/mod_login.tpl#L28), [`38`](../src/punbb/mod_login.tpl#L38)
* __[`{L_MESSAGES}`](https://github.com/Etana/template/blob/master/var/L_MESSAGES.md#readme)<a href="https://fa-tvars.appspot.com/var/L_MESSAGES">*</a> :__ ligne [`50`](../src/punbb/mod_login.tpl#L50)
* __[`{L_MY_PROFILE}`](https://github.com/Etana/template/blob/master/var/L_MY_PROFILE.md#readme)<a href="https://fa-tvars.appspot.com/var/L_MY_PROFILE">*</a> :__ ligne [`54`](../src/punbb/mod_login.tpl#L54)
* __[`{L_PASSWORD}`](https://github.com/Etana/template/blob/master/var/L_PASSWORD.md#readme) :__ lignes [`12`](../src/punbb/mod_login.tpl#L12), [`34`](../src/punbb/mod_login.tpl#L34)
* __[`{L_PM}`](https://github.com/Etana/template/blob/master/var/L_PM.md#readme) :__ ligne [`52`](../src/punbb/mod_login.tpl#L52)
* __[`{L_SEND_PASSWORD}`](https://github.com/Etana/template/blob/master/var/L_SEND_PASSWORD.md#readme)<a href="https://fa-tvars.appspot.com/var/L_SEND_PASSWORD">*</a> :__ lignes [`14`](../src/punbb/mod_login.tpl#L14), [`36`](../src/punbb/mod_login.tpl#L36)
* __[`{L_USERNAME}`](https://github.com/Etana/template/blob/master/var/L_USERNAME.md#readme) :__ lignes [`8`](../src/punbb/mod_login.tpl#L8), [`32`](../src/punbb/mod_login.tpl#L32)
* __[`{NB_MESSAGES}`](https://github.com/Etana/template/blob/master/var/NB_MESSAGES.md#readme)<a href="https://fa-tvars.appspot.com/var/NB_MESSAGES">*</a> :__ ligne [`51`](../src/punbb/mod_login.tpl#L51)
* __[`{NB_PM_READ}`](https://github.com/Etana/template/blob/master/var/NB_PM_READ.md#readme)<a href="https://fa-tvars.appspot.com/var/NB_PM_READ">*</a> :__ ligne [`53`](../src/punbb/mod_login.tpl#L53)
* __[`{NB_PM_UNREAD}`](https://github.com/Etana/template/blob/master/var/NB_PM_UNREAD.md#readme)<a href="https://fa-tvars.appspot.com/var/NB_PM_UNREAD">*</a> :__ ligne [`53`](../src/punbb/mod_login.tpl#L53)
* __[`{S_LOGIN_ACTION}`](https://github.com/Etana/template/blob/master/var/S_LOGIN_ACTION.md#readme) :__ lignes [`5`](../src/punbb/mod_login.tpl#L5), [`30`](../src/punbb/mod_login.tpl#L30)
* __[`{USERNAME}`](https://github.com/Etana/template/blob/master/var/USERNAME.md#readme)<a href="https://fa-tvars.appspot.com/var/USERNAME">*</a> :__ lignes [`9`](../src/punbb/mod_login.tpl#L9), [`33`](../src/punbb/mod_login.tpl#L33), [`44`](../src/punbb/mod_login.tpl#L44)
* __[`{USERNAME_AVATAR}`](https://github.com/Etana/template/blob/master/var/USERNAME_AVATAR.md#readme)<a href="https://fa-tvars.appspot.com/var/USERNAME_AVATAR">*</a> :__ ligne [`47`](../src/punbb/mod_login.tpl#L47)
* __[`{U_PROFILE}`](https://github.com/Etana/template/blob/master/var/U_PROFILE.md#readme) :__ ligne [`54`](../src/punbb/mod_login.tpl#L54)
* __[`{U_SEND_PASSWORD}`](https://github.com/Etana/template/blob/master/var/U_SEND_PASSWORD.md#readme)<a href="https://fa-tvars.appspot.com/var/U_SEND_PASSWORD">*</a> :__ lignes [`14`](../src/punbb/mod_login.tpl#L14), [`36`](../src/punbb/mod_login.tpl#L36)
* __[`<!-- BEGIN switch_login -->`](https://github.com/Etana/template/blob/master/var/switch_login.md#readme)<a href="https://fa-tvars.appspot.com/var/switch_login">*</a> :__ ligne [`2`](../src/punbb/mod_login.tpl#L2)
* __[`<!-- END switch_login -->`](https://github.com/Etana/template/blob/master/var/switch_login.md#readme) :__ ligne [`25`](../src/punbb/mod_login.tpl#L25)
* __[`<!-- BEGIN switch_login_small -->`](https://github.com/Etana/template/blob/master/var/switch_login_small.md#readme)<a href="https://fa-tvars.appspot.com/var/switch_login_small">*</a> :__ ligne [`27`](../src/punbb/mod_login.tpl#L27)
* __[`<!-- END switch_login_small -->`](https://github.com/Etana/template/blob/master/var/switch_login_small.md#readme) :__ ligne [`41`](../src/punbb/mod_login.tpl#L41)
* __[`<!-- BEGIN switch_profile -->`](https://github.com/Etana/template/blob/master/var/switch_profile.md#readme)<a href="https://fa-tvars.appspot.com/var/switch_profile">*</a> :__ ligne [`43`](../src/punbb/mod_login.tpl#L43)
* __[`<!-- END switch_profile -->`](https://github.com/Etana/template/blob/master/var/switch_profile.md#readme) :__ ligne [`57`](../src/punbb/mod_login.tpl#L57)


## Template par défaut phpBB2

[__Code source__](../src/subsilver/mod_login.tpl#files)

### Positions des variables 

* __[`{AUTOLOGIN_CHECKED}`](https://github.com/Etana/template/blob/master/var/AUTOLOGIN_CHECKED.md#readme) :__ lignes [`21`](../src/subsilver/mod_login.tpl#L21), [`56`](../src/subsilver/mod_login.tpl#L56)
* __[`{DIRECTION}`](https://github.com/Etana/template/blob/master/var/DIRECTION.md#readme)<a href="https://fa-tvars.appspot.com/var/DIRECTION">*</a> :__ lignes [`83`](../src/subsilver/mod_login.tpl#L83), [`84`](../src/subsilver/mod_login.tpl#L84), [`84`](../src/subsilver/mod_login.tpl#L84)
* __[`{L_AUTO_LOGIN}`](https://github.com/Etana/template/blob/master/var/L_AUTO_LOGIN.md#readme) :__ lignes [`21`](../src/subsilver/mod_login.tpl#L21), [`56`](../src/subsilver/mod_login.tpl#L56)
* __[`{L_LOGIN}`](https://github.com/Etana/template/blob/master/var/L_LOGIN.md#readme) :__ lignes [`5`](../src/subsilver/mod_login.tpl#L5), [`24`](../src/subsilver/mod_login.tpl#L24), [`42`](../src/subsilver/mod_login.tpl#L42), [`59`](../src/subsilver/mod_login.tpl#L59)
* __[`{L_MESSAGES}`](https://github.com/Etana/template/blob/master/var/L_MESSAGES.md#readme)<a href="https://fa-tvars.appspot.com/var/L_MESSAGES">*</a> :__ ligne [`85`](../src/subsilver/mod_login.tpl#L85)
* __[`{L_MY_PROFILE}`](https://github.com/Etana/template/blob/master/var/L_MY_PROFILE.md#readme)<a href="https://fa-tvars.appspot.com/var/L_MY_PROFILE">*</a> :__ ligne [`87`](../src/subsilver/mod_login.tpl#L87)
* __[`{L_PASSWORD}`](https://github.com/Etana/template/blob/master/var/L_PASSWORD.md#readme) :__ lignes [`17`](../src/subsilver/mod_login.tpl#L17), [`53`](../src/subsilver/mod_login.tpl#L53)
* __[`{L_PM}`](https://github.com/Etana/template/blob/master/var/L_PM.md#readme) :__ ligne [`86`](../src/subsilver/mod_login.tpl#L86)
* __[`{L_SEND_PASSWORD}`](https://github.com/Etana/template/blob/master/var/L_SEND_PASSWORD.md#readme)<a href="https://fa-tvars.appspot.com/var/L_SEND_PASSWORD">*</a> :__ lignes [`28`](../src/subsilver/mod_login.tpl#L28), [`62`](../src/subsilver/mod_login.tpl#L62)
* __[`{L_USERNAME}`](https://github.com/Etana/template/blob/master/var/L_USERNAME.md#readme) :__ lignes [`13`](../src/subsilver/mod_login.tpl#L13), [`50`](../src/subsilver/mod_login.tpl#L50)
* __[`{NB_MESSAGES}`](https://github.com/Etana/template/blob/master/var/NB_MESSAGES.md#readme)<a href="https://fa-tvars.appspot.com/var/NB_MESSAGES">*</a> :__ ligne [`85`](../src/subsilver/mod_login.tpl#L85)
* __[`{NB_PM_READ}`](https://github.com/Etana/template/blob/master/var/NB_PM_READ.md#readme)<a href="https://fa-tvars.appspot.com/var/NB_PM_READ">*</a> :__ ligne [`86`](../src/subsilver/mod_login.tpl#L86)
* __[`{NB_PM_UNREAD}`](https://github.com/Etana/template/blob/master/var/NB_PM_UNREAD.md#readme)<a href="https://fa-tvars.appspot.com/var/NB_PM_UNREAD">*</a> :__ ligne [`86`](../src/subsilver/mod_login.tpl#L86)
* __[`{S_LOGIN_ACTION}`](https://github.com/Etana/template/blob/master/var/S_LOGIN_ACTION.md#readme) :__ lignes [`10`](../src/subsilver/mod_login.tpl#L10), [`47`](../src/subsilver/mod_login.tpl#L47)
* __[`{USERNAME}`](https://github.com/Etana/template/blob/master/var/USERNAME.md#readme)<a href="https://fa-tvars.appspot.com/var/USERNAME">*</a> :__ lignes [`14`](../src/subsilver/mod_login.tpl#L14), [`50`](../src/subsilver/mod_login.tpl#L50), [`75`](../src/subsilver/mod_login.tpl#L75)
* __[`{USERNAME_AVATAR}`](https://github.com/Etana/template/blob/master/var/USERNAME_AVATAR.md#readme)<a href="https://fa-tvars.appspot.com/var/USERNAME_AVATAR">*</a> :__ ligne [`83`](../src/subsilver/mod_login.tpl#L83)
* __[`{U_PROFILE}`](https://github.com/Etana/template/blob/master/var/U_PROFILE.md#readme) :__ ligne [`87`](../src/subsilver/mod_login.tpl#L87)
* __[`{U_SEND_PASSWORD}`](https://github.com/Etana/template/blob/master/var/U_SEND_PASSWORD.md#readme)<a href="https://fa-tvars.appspot.com/var/U_SEND_PASSWORD">*</a> :__ lignes [`28`](../src/subsilver/mod_login.tpl#L28), [`62`](../src/subsilver/mod_login.tpl#L62)
* __[`<!-- BEGIN switch_login -->`](https://github.com/Etana/template/blob/master/var/switch_login.md#readme)<a href="https://fa-tvars.appspot.com/var/switch_login">*</a> :__ ligne [`1`](../src/subsilver/mod_login.tpl#L1)
* __[`<!-- END switch_login -->`](https://github.com/Etana/template/blob/master/var/switch_login.md#readme) :__ ligne [`36`](../src/subsilver/mod_login.tpl#L36)
* __[`<!-- BEGIN switch_login_small -->`](https://github.com/Etana/template/blob/master/var/switch_login_small.md#readme)<a href="https://fa-tvars.appspot.com/var/switch_login_small">*</a> :__ ligne [`38`](../src/subsilver/mod_login.tpl#L38)
* __[`<!-- END switch_login_small -->`](https://github.com/Etana/template/blob/master/var/switch_login_small.md#readme) :__ ligne [`69`](../src/subsilver/mod_login.tpl#L69)
* __[`<!-- BEGIN switch_profile -->`](https://github.com/Etana/template/blob/master/var/switch_profile.md#readme)<a href="https://fa-tvars.appspot.com/var/switch_profile">*</a> :__ ligne [`71`](../src/subsilver/mod_login.tpl#L71)
* __[`<!-- END switch_profile -->`](https://github.com/Etana/template/blob/master/var/switch_profile.md#readme) :__ ligne [`95`](../src/subsilver/mod_login.tpl#L95)
