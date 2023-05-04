# silverstripe-admin-edit-link

## Use jonom/silverstripe-betternavigator and optionally jonom/silverstripe-environment-awareness for a more complete/user-friendly solution

Adds a link to the CMS edit page if logged in user has appropriate permissions. This works by detecting the meta[name="x-cms-edit-link"] header tag.
This tiny module has no dependancies other than Silverstripe 4.

## Installation
`composer require Pikselin/silverstripe-admin-edit-link`

## CSS
The CSS for this is very basic and can be overridden:
```
.cms-edit-link {
    position: absolute;
    padding: 0.5rem;
    bottom: 15px;
    right: 15px;
    background-color: #ffffff;
    color: #002752;
}
```
