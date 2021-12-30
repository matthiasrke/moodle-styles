# Dark Mode
You can use this code, for example, to adjust the background in a breakout room to a spooky atmosphere.

Tested in Moodle 3.9, 3.10 and 3.11

``` CSS
<style>
body,
#nav-drawer {
    background-color: #000;
}
section#region-main {
    color: #fff;
    background-color: #000;
}
a,
.btn-link {
    color: #0088fd;
}
a:hover,
a:not([class]):focus,
.btn-link:hover,
.btn-link:focus,
a.aalink:focus  {
    color: #319fff;
}
@media screen and (min-width: 576px) {
    body,
    #page,
    .activity-navigation {
        background-color: #000;
    }
}
</style>
```