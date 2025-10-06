<img width="1597" height="874" alt="doc_2025-10-06_20-52-46" src="https://github.com/user-attachments/assets/7ed1b275-1693-4f3f-bdb4-e41d0275becd" />

Just Standart linux logo with no stuck problem cause potato laptop

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
$sudo cp -r {YOUR EXTRACT DIRECTORY} /usr/share/plymouth/themes
$sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/linux-logo/linux-logo.plymouth 250
$sudo update-alternatives --config default.plymouth
$sudo update-initramfs -u
///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
