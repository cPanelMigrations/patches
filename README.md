FB updateuserdomains-universal 82433

Steps to use:

1. on the cPanel server:

   # mkdir -p /var/cpanel/lib/Whostmgr/Pkgacct/

   # cd /var/cpanel/lib/Whostmgr/Pkgacct/
2. wget https://raw.github.com/cPanelMigrations/patches/master/updateuserdomains-universal_FB-82433
3. mv updateuserdomains-universal_FB-82433 updateuserdomains-universal
4. chmod +x updateuserdomains-universal
5. run the migration using the allow-override option
