# FreeBSD 14.0-RELEASE ZFS module load error

When using CirrusCI (GCE), and attempting to load the ZFS module, the
following error appears:

    link_elf_obj: symbol vfs_exjail_clone undefined
    linker_load_file: /boot/kernel/zfs.ko - unsupported file type
