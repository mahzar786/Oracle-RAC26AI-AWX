AWX RAC26AI Project Skeleton

Recommended workflow:
00_environment_validation.yml
01_cleanup_old_rac.yml
02_prereq_check.yml
03_os_prepare.yml
04_users_dirs.yml
05_hosts_ssh.yml
06a_discover_disk_uid.yml
06b_validate_asm_disks.yml
06c_clean_asm_disks.yml
06d_create_asm_udev.yml
07_stage_software.yml
08_install_grid.yml
08a_create_data_fra_diskgroups.yml
09_install_db_home.yml
10_create_rac_database.yml
11_post_validation.yml
12_cluster_report.yml

NOTE:
This archive is a project skeleton reflecting your lab environment.
The Grid response files, DBCA response files, CVU checks, SSH equivalence,
and root script orchestration still need to be completed and tested.
