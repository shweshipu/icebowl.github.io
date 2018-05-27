Gentoo


ciclo /usr/src # cp linux-4.9.76-gentoo-r1/.config linux-4.9.95-gentoo/
ciclo /usr/src/linux-4.9.95-gentoo # make && make modules_install && make install && mount /boot && boot-update 
