Experiment 8

Write shell scripts to print system information.
Implementation:
echo "System Information:"
echo $(lscpu)
![Answer(Sysinfo)](https://github.com/user-attachments/assets/de9aa242-f001-4e9b-ab03-65a35c8ec039)

Write shell script to perform basic mathematical calculation.
Implementation:
echo "Enter num1: "
read num1
echo "enter num2: "
read num2
echo Addition: $((num1 + num2))
echo Subtrafction: $((num1 - num2))
echo Multi: $((num1 * num2))
if [ $num2 -ne 0 ] ;
then
echo Divide; $((num1/num2))
else
echo undefined
fi
![Answer(Math)](https://github.com/user-attachments/assets/f1aaf83d-09fe-4cc4-971e-9d694ff2fc6e)


