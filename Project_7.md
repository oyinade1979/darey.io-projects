##Devops Tooling Website Solution



`devices volumes created successfully`
<img width="448" alt="device_volume" src="https://user-images.githubusercontent.com/69362725/173199144-68616667-870b-4d21-b70d-1abcc8a30c2e.png">


`devices volumes partition created successfully`
<img width="538" alt="Partition_created_successfully" src="https://user-images.githubusercontent.com/69362725/173199166-4340cb64-a231-4631-aa3a-d15bd26cf643.png">

`install lvm2`
<img width="960" alt="sudo_yum_install_lvm2_-y" src="https://user-images.githubusercontent.com/69362725/173199182-dff57bf2-0314-4a98-b907-d8aab86a3908.png">

`check for available partition`

<img width="577" alt="check_available_partition" src="https://user-images.githubusercontent.com/69362725/173199197-76fb9e28-da8a-42cb-afa7-ca0d6b64e525.png">


`physical volume created for available partition`

<img width="424" alt="Physical_volume_created_successfully" src="https://user-images.githubusercontent.com/69362725/173199212-9ba46d39-d366-4804-8f17-88f91d53a024.png">

`check physical volume created for available partition`

<img width="362" alt="check_physical_vol_created_successfully" src="https://user-images.githubusercontent.com/69362725/173199222-de707c96-5f2b-49c0-8c1e-389449daf8ba.png">


`volume group created for webdata-vg available partition`

<img width="668" alt="created_webdata-vg" src="https://user-images.githubusercontent.com/69362725/173199242-0893fe76-37b9-4ede-a117-f397b0c8ff49.png">


`check size for three webdata-vg available partition created`

<img width="398" alt="check_size_for_3_webdata" src="https://user-images.githubusercontent.com/69362725/173199248-75115a70-c70f-44dc-b171-7b56b17d1237.png">


`logical volume created`

<img width="550" alt="create_logical_vloume" src="https://user-images.githubusercontent.com/69362725/173199255-2db1ddf8-3351-4a5a-aac2-73e6cfe6d770.png">


`Check logical volume created successfully`

<img width="674" alt="check_logical_vol_created_successfully" src="https://user-images.githubusercontent.com/69362725/173199268-8894332a-ad88-4fbf-8871-ce44835c71dc.png">


`Check logical and physical volume attached successfully`

<img width="568" alt="check_ataached_partition_correctly" src="https://user-images.githubusercontent.com/69362725/173199279-377c2e6b-f2d2-4527-960a-e1f08c18fea8.png">.png)

`format disk as xfs`

<img width="677" alt="format_disk_as_xfs_logs_app_opt" src="https://user-images.githubusercontent.com/69362725/173199319-f84ab3a9-6191-4dc9-8d4b-b943375cafaf.png">.png)

`mount logical volumes on mnt`

<img width="572" alt="mount_logical_volumes_app_logs_opt" src="https://user-images.githubusercontent.com/69362725/173199326-aff4d925-51b9-433f-8a66-3838e695c102.png">


`install NFS server`

<img width="853" alt="install_update" src="https://user-images.githubusercontent.com/69362725/173199341-9ecbc7d2-0b55-47fb-8943-a2b33e431cdd.png">

<img width="860" alt="install_nfs_utils" src="https://user-images.githubusercontent.com/69362725/173199350-01830fd1-fd02-4721-b0fd-4332e0043b6c.png">

<img width="868" alt="install_completion_process" src="https://user-images.githubusercontent.com/69362725/173199363-e741023e-306d-47f4-804c-1839c5cedb83.png">.png)

`permission allow webservers read write execute files on NFS`

<img width="565" alt="permission_allow_webservers_read_write_execute_files_on_NFS" src="https://user-images.githubusercontent.com/69362725/173199410-e76a1cd0-8fdb-43c4-93a4-e12e881d1c9f.png">


`Configure access to NFS for clients within the same subnet`

<img width="415" alt="Configure_access_to_NFS_for_clients_within_the_same_subnet" src="https://user-images.githubusercontent.com/69362725/173199428-469e2b44-4448-4992-a52e-cc0165ef2e5a.png">

<img width="865" alt="Configure_access_to_NFS_for_clients_within_the_same_subnet2" src="https://user-images.githubusercontent.com/69362725/173199438-0766c940-1d07-41b4-9462-7d4b15de9c01.png">

<img width="431" alt="Configure_access_to_NFS_for_clients_within_the_same_subnet3" src="https://user-images.githubusercontent.com/69362725/173199458-88387317-8e2d-4c03-9e52-859a1b1267a4.png">

`check port used by NFS`

<img width="518" alt="check_port_used_NFS" src="https://user-images.githubusercontent.com/69362725/173199471-2222d0f5-33cc-433f-be65-2326fe18b13f.png">

`NFS added surity inbound rules`

<img width="866" alt="aws_security_inbound_rules" src="https://user-images.githubusercontent.com/69362725/173199486-4372aa88-da00-473f-8d95-08650c8484c7.png">


`create mysql server DB enter sudo apt install mysql-server -y`

<img width="865" alt="create_mysql_server_DB_sudo_apt_install_mysql-server_-y" src="https://user-images.githubusercontent.com/69362725/173199505-123d6000-f0e9-430c-bb91-a18bb731b86a.png">

`open my sql`

<img width="688" alt="Navigate_into_mysql" src="https://user-images.githubusercontent.com/69362725/173199514-ae23150c-2a25-496a-bbc2-5c6b8dabdad7.png">


`create user for mysql for db connect aws webserver1 networking subnetid copy IPv4 CIDR`

<img width="560" alt="create_user_db_coonect_aws_webserver1_networking_subnetid" src="https://user-images.githubusercontent.com/69362725/173199545-c7a48a52-7723-4c17-a583-3cbf31650a75.png">


`grant all priviledges`

<img width="568" alt="grant_all_priviledges" src="https://user-images.githubusercontent.com/69362725/173199567-66e4f974-0a92-4d9f-b1e9-4494b1bb1f3d.png">

`tooling not shown in database after grant all access`

<img width="568" alt="tooling_not_shown_in_database_after_grant_all_access" src="https://user-images.githubusercontent.com/69362725/173199579-04122908-ebf2-47f0-81de-fc610dc6011f.png">


`resolution tooling shown in database after grant all access`

<img width="856" alt="resolution_tooling_shown_in_database_after_grant_all_access" src="https://user-images.githubusercontent.com/69362725/173199589-67ab9a0c-6aef-4b3e-a332-0a2a0aa72be9.png">

`install NFS Client`

<img width="863" alt="install_NFS_Client" src="https://user-images.githubusercontent.com/69362725/173199603-11dd3a3e-775d-4241-88b7-2470b84dbb5d.png">


`mount NFS Server export for apps`

<img width="784" alt="mount_var_www_NFS_Server_export_for_apps" src="https://user-images.githubusercontent.com/69362725/173199620-0203c5fb-5d36-4701-b3f8-4df7f31fe262.png">


`Verify NFS mounted`
<img width="491" alt="verify_NFS_Mounted" src="https://user-images.githubusercontent.com/69362725/173199637-57871dad-ca59-4e43-ad3e-73a0109aa618.png">

<img width="862" alt="AWS_NFS_Private_IP_Address_and_following_line" src="https://user-images.githubusercontent.com/69362725/173199664-67174a3f-3c8b-4f48-8b76-642b2f0b9962.png">


`Install apache`

<img width="465" alt="install_apache" src="https://user-images.githubusercontent.com/69362725/173199701-4d277135-1540-4e68-8b0e-7582d893b722.png">

<img width="618" alt="install_apache_successfully" src="https://user-images.githubusercontent.com/69362725/173199708-35752462-68dd-453d-8f1c-a377e1be3c15.png">

<img width="849" alt="install_apache_successfully3" src="https://user-images.githubusercontent.com/69362725/173199729-8751f467-2f56-4992-801e-4a394ff439cc.png">

<img width="860" alt="install_apache_successfully4" src="https://user-images.githubusercontent.com/69362725/173199749-13e0e6c6-70ce-45ba-a035-8a9afe7a8212.png">

<img width="867" alt="install_apache_successfully5" src="https://user-images.githubusercontent.com/69362725/173199757-a79f03af-c882-488f-8f6d-2b7ee7887118.png">

<img width="866" alt="install_apache_successfully6" src="https://user-images.githubusercontent.com/69362725/173199769-2c0e6798-1246-4156-8325-224b5cebbbfe.png">

<img width="863" alt="install_apache_completedsteps" src="https://user-images.githubusercontent.com/69362725/173199774-736f8552-08b2-48cd-9c46-c33530a91286.png">


`Install apache Logs`

<img width="819" alt="install_log_apache" src="https://user-images.githubusercontent.com/69362725/173199786-64abc75e-4b20-4e42-ab57-bf4b45bd5d54.png">


`Clone Github`

<img width="863" alt="clone_github_encountered_error_and_resolved" src="https://user-images.githubusercontent.com/69362725/173199797-0135c5b8-a1d1-432d-9c28-47f1e606162e.png">


`Add inbound rule for webserver1`

<img width="878" alt="webserver1_security_editinboundrules" src="https://user-images.githubusercontent.com/69362725/173199810-7646b632-a045-4c66-aa1e-7082cd54c846.png">


`Error when connect to public from aws`

<img width="727" alt="rectify_error_url_public_aws_used" src="https://user-images.githubusercontent.com/69362725/173199830-8e8f487d-9202-4dc8-95e6-1efed9fb1212.png">

`changed to enabled`

<img width="863" alt="changed_to_enabled" src="https://user-images.githubusercontent.com/69362725/173199844-9ac55cda-1482-4eb4-8ce8-75d3053dabf3.png">


`restart apache`

<img width="867" alt="restart_apache" src="https://user-images.githubusercontent.com/69362725/173199859-de92015b-12cd-4013-8d89-87d8b9b6c733.png">


`configure password`

<img width="701" alt="configure_password" src="https://user-images.githubusercontent.com/69362725/173199873-8dbaef24-004e-4e8c-9706-2b54447872a6.png">

<img width="865" alt="configure_details_correctly" src="https://user-images.githubusercontent.com/69362725/173199889-2c2447f3-5c37-473b-9857-379ccb42ce06.png">


`install mysql`

<img width="858" alt="install_mysql" src="https://user-images.githubusercontent.com/69362725/173199907-4e059eec-813d-4440-b19d-a291a0b2a76e.png">


`setup inbound rules on db`

<img width="914" alt="setup_security_inbound_rules_DB" src="https://user-images.githubusercontent.com/69362725/173199913-9785ab66-7da2-43d4-8f1c-5c558b8b2dd1.png">


`check mysql bind`

<img width="866" alt="check_mysql_bind" src="https://user-images.githubusercontent.com/69362725/173199932-2b57be70-35ce-4e8a-821e-5fbde2a3749b.png">


`change bind address to 0`

<img width="866" alt="change_bind_address_to_0" src="https://user-images.githubusercontent.com/69362725/173199952-ce03d179-5764-4ee2-97da-835ed1b76a14.png">


`restart mysql`

<img width="872" alt="restart_mysql2" src="https://user-images.githubusercontent.com/69362725/173199963-7150990d-8f4a-473b-9aef-7a89dcace5c0.png">


`Apply tooling-db.sql script to your database`
<img width="863" alt="Apply_tooling-db sql_script_to_database" src="https://user-images.githubusercontent.com/69362725/173199980-f6621dd7-9241-477c-b78a-602fead8ade7.png">


`mysql show database tables`
<img width="865" alt="mysql_show_database_tables" src="https://user-images.githubusercontent.com/69362725/173200007-022412de-df86-4cee-96ca-c88fdf8eb1e3.png">

<img width="863" alt="create_user" src="https://user-images.githubusercontent.com/69362725/173200018-a30cf33a-0608-47e4-a113-0bc9d44c5c22.png">

`login page`

<img width="946" alt="login_page" src="https://user-images.githubusercontent.com/69362725/173200032-32a2a44b-ad05-459c-9d31-4125c3202965.png">

`login_successgully_username_password_admin`

<img width="943" alt="login_successgully_username_password_admin" src="https://user-images.githubusercontent.com/69362725/173200044-ee120d1a-8391-4b24-8a37-64dca506a2e8.png">
