# rk3506-rkr4.2-sdk


## Compilation steps

### Select profile

Enter the top-level directory of SDK source code, execute the following command, and select the board level configuration file

```
./build.sh lunch
1. rockchip_rk3502_robot_defconfig
2. rockchip_rk3506_b_evb1_defconfig
3. rockchip_rk3506_g_demo_defconfig
4. rockchip_rk3506_g_evb1_amp_defconfig
5. rockchip_rk3506_g_evb1_defconfig
6. rockchip_rk3506_g_evb1_smp_defconfig
7. rockchip_rk3506j_armsom_cm1_defconfig
8. rockchip_rk3506j_armsom_forge1_defconfig
```

Choose 7 or 8.



### Compilation

After selecting the board level configuration, compile it completely once directly

```
./build.sh
```

The generated image file is in the `SDK/rockdev` folder

Compile the Uboot:

```
./build.sh uboot
```

Compile the Kernel:

```
./build.sh kernel
```

