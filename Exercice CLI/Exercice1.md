mkdir cli_tmp
cd cli_tmp
touch je_suis_dans_tmp.txt
touch in_cli_tmp.txt
mkdir in_cli_tmp
rm je_suis_dans_tmp.txt
cd ..
rm -rf cli_tmp
mkdir grand_parent parent grand_frere grande_soeur ami connaissances
cd grand_frere
touch bachir.txt
mv bachir.txt ../ami
cd ..
cp -r ami parent
pwd
cd ~

