# Frappe Commands and Issues

#### Installation of Frappe https://github.com/D-codE-Hub/Frappe-ERPNext-Version-14--in-Ubuntu-22.04-LTS

### Create a bench with Version

```
bench init frappe-bench --frappe-branch version-14
```
<br>

### Create an App on the bench.

<br>

I want to install library_management and the command is below.

<br>

```
bench new-app library_management
```

<br>

### Create a Site on the bench.

<br>

I want to install the library.com site and the command is below.

<br>

```
bench new-site library.test
```

<br>

### Set current site for bench

<br>

```
bench use library.com
```

<br>

### If you want to Developer Mode

<br>

```
bench set-config -g developer_mode true
```
