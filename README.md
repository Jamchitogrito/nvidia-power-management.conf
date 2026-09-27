sudo tee /etc/modprobe.d/nvidia-power-management.conf <<EOF
options nvidia NVreg_DynamicPowerManagement=0x02
EOF
