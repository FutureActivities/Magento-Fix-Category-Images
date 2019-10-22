# Fix Category Images

This is a small extension which fixes [this bug](https://github.com/magento/magento2/issues/25099) of category
images being removed when the category is saved.

This bug affects only Magento 2.3.3. 

This can be removed once updated.

## Install

Clone this repo to `app/code/FutureActivities/FixCategoryImages`
and then run the following commands:

    bin/magento module:enable FutureActivities_FixCategoryImages
    bin/magento setup:upgrade
    bin/magento setup:di:compile