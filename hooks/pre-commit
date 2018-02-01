#!/bin/bash

branch=$(git rev-parse --abbrev-ref HEAD)

printf "Sedang di branch \e[33m$branch\e[0m\n"  
echo "Lanjutkan commit?"  
select yn in "Ya" "Tidak"; do  
    case $yn in
        Ya ) exit 0; break;;
        Tidak ) exit 1;;
    esac
done