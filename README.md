# Product-Anti-theft-System-On-FPGA
You can check if a returned product is stolen or discounted by entering its UPC code. To save costs, only expensive products are tagged when sold. Therefore, if a returned product is expensive and doesn't have a tag, we can identify it as stolen.

The SW[9:7] is designed for enter UPC code, and the SW[0] is to detect whether the product has a mark on it. LEDR1 is for discounted status, and LEDR0 is represent whether it's a stolen product, and we can only know whether an expensive product has ever been stolen.
