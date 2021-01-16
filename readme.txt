cd ~
rm -rf cpanel_defaultwebpage.html
rm -rf /var/www/html/index.html
wget -O cpanel_defaultwebpage.html https://raw.githubusercontent.com/ninzahost/cpanel_defaultwebpage/main/index.html
cp cpanel_defaultwebpage.html /var/www/html/index.html
cd ~
rm -rf cpanel_defaultwebpage.html
