# avsdpll_3v3 - OnChip PLL Clock Multiplier 

### Specifications
    - ClockIn  5MHz  to 12MHz  at 1.8v
    - ClockOut 40MHz to 100MHz at 1.8v
    - 8x multiplication

This repository hosts relevant files on the IP.

### Folder Hierarchy
00. [Specifications](https://github.com/eddygta17/avsdpll_3v3/tree/master/00.Specifications) - Specifications provided for the PLL.
01. [Reports](https://github.com/eddygta17/avsdpll_3v3/tree/master/01.Reports) - Reports and presentations.
02. [Schematic](https://github.com/eddygta17/avsdpll_3v3/tree/master/02.Schematic) - Schematic of different components.
    1. [PFD](https://github.com/eddygta17/avsdpll_3v3/tree/master/02.Schematic/i.PFD)
    2. [DIV2](https://github.com/eddygta17/avsdpll_3v3/tree/master/02.Schematic/ii.DIV2)
    3. [VCO](https://github.com/eddygta17/avsdpll_3v3/tree/master/02.Schematic/iii.VCO)
    4. [Charge Pump](https://github.com/eddygta17/avsdpll_3v3/tree/master/02.Schematic/iv.ChargePump)
    5. [PLL](https://github.com/eddygta17/avsdpll_3v3/tree/master/02.Schematic/v.PLL)

## Pre-layout Simulation of PLL 
1. Input Frequency (F_in) = 5MHz
![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/400c6b86-82e6-41e9-bc9b-960f7387363a/Fin5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200824%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200824T133524Z&X-Amz-Expires=86400&X-Amz-Signature=c43d61cac81e02ea4207fdec7fd99d08554ef8612ad6453723e1537e2cc7250e&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Fin5.png%22)
![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/5be70fdf-fd24-4617-99a2-789fb56e9b0f/Fclose5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200824%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200824T140504Z&X-Amz-Expires=86400&X-Amz-Signature=1bdcb6880effb4357aaf39aeee8105bc3f323521068815956a8eb494a680df3f&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Fclose5.png%22)
2. Input Frequency (F_in) = 10MHz
![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/e035dd20-ee3c-4025-8c5a-894b6673278e/Fin10.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200824%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200824T133441Z&X-Amz-Expires=86400&X-Amz-Signature=d4546c94eb1133c4ae25f527b9c10b897eb050689ec425acb3ba7b975d57e580&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Fin10.png%22)
![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/4cf97de3-60cb-4884-a250-1dccd5eaf8fb/Fclose10.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20200824%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20200824T140919Z&X-Amz-Expires=86400&X-Amz-Signature=28e7c96f4a5efcb5fc8110e529193c8d6b7809c31a907bed9bce831c7fec9f2f&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Fclose10.png%22)

### Contributors
- **Abel Joseph John** 
- **Kunal Promode Ghosh** 
- **Philipp Gühring** 

### Acknowledgments
- Kunal Promode Ghosh, Director, VSD Corp. Pvt. Ltd.
- Philipp Gühring, Software Architect, LibreSilicon Assocation
