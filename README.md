# 3Scale Guides

## Pre-req

* 3Scale working

## Guides

### Application Name on Backend

#### Create API Product

![](res/2020-03-30-19-10-50.png)

![](res/2020-03-30-19-13-25.png)

#### Create Backend

![](res/2020-03-30-19-15-18.png)

![](res/2020-03-30-19-16-40.png)

#### Add backend to the API

![](res/2020-03-30-19-17-43.png)

![](res/2020-03-30-19-18-27.png)

![](res/2020-03-30-19-19-08.png)

#### Create Application Plan

![](res/2020-03-30-19-23-53.png)

![](res/2020-03-30-19-24-54.png)

![](res/2020-03-30-19-25-27.png)

#### Create an Application

![](res/2020-03-30-19-26-58.png)

![](res/2020-03-30-19-27-56.png)

![](res/2020-03-30-19-28-26.png)

![](res/2020-03-30-19-29-41.png)

#### Promoto to Staging

![](res/2020-03-30-19-30-58.png)

#### Change user-key to HTTP Header

![](res/2020-03-30-19-39-47.png)

In the same page, click on "Update Product"

![](res/2020-03-30-19-40-45.png)

Now promote to staging again

![](res/2020-03-30-19-45-04.png)

#### Change user-key format

![](res/2020-03-30-19-41-51.png)

![](res/2020-03-30-19-42-21.png)

![](res/2020-03-30-19-43-11.png)

![](res/2020-03-30-19-44-41.png)

#### Create Policy

![](res/2020-03-30-19-47-00.png)

![](res/2020-03-30-19-47-21.png)

![](res/2020-03-30-19-47-57.png)

Make sure Header policy come first than 3Scale APIcast

![](res/2020-03-30-19-48-58.png)

Now click on `Header modification`

![](res/2020-03-30-19-49-40.png)

![](res/2020-03-30-19-50-02.png)

![](res/2020-03-30-19-52-03.png)

![](res/2020-03-30-19-52-21.png)

#### Promote to Staging again

![](res/2020-03-30-19-52-59.png)

![](res/2020-03-30-19-53-34.png)

#### Test

![](res/2020-03-30-19-54-16.png)

![](res/2020-03-30-19-55-48.png)

### Route based on path

#### Create API Product for Route Path

Create a new API Product using the same steps described on the instructions for the item `Application Name on Backend`

![](res/2020-03-31-21-59-11.png)

#### Create Application Plan

![](res/2020-03-31-22-00-43.png)

![](res/2020-03-31-22-01-10.png)

#### Create an Application

![](res/2020-03-31-22-02-48.png)

#### Create Backend 01

![](res/2020-03-31-22-06-05.png)

#### Create Backend 02

![](res/2020-03-31-22-08-18.png)

#### Add backend 01 to API

![](res/2020-03-31-22-09-35.png)

![](res/2020-03-31-22-10-08.png)

#### Add backend 01 to API

![](res/2020-03-31-22-09-35.png)

![](res/2020-03-31-22-10-54.png)

Now, you should have this:

![](res/2020-03-31-22-11-25.png)

#### Create Mapping Rules for Your API Product

![](res/2020-03-31-22-16-06.png)

#### Promote your API

![](res/2020-03-31-22-12-24.png)

#### Test Route Path

![](res/2020-03-31-22-18-28.png)

![](res/2020-03-31-22-19-24.png)