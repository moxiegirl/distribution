+++
title = "Filesystem storage driver"
description = "Explains how to use the filesystem storage drivers"
keywords = ["registry, service, driver, images, storage,  filesystem"]
[menu.main]
parent= "smn_registry" 
+++


# Filesystem storage driver

An implementation of the `storagedriver.StorageDriver` interface which uses the local filesystem.

## Parameters

`rootdirectory`: (optional) The root directory tree in which all registry files will be stored. Defaults to `/tmp/registry/storage`.
