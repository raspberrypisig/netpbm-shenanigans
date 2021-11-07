# netpbm-shenanigans

1. Start with monochrome PNG file scaled to below (96x32)
   - example, use feep.png (24x7)
2. Imagemagick command
   ```
   convert feep.png -monochrome feep.pbm
   ```
3. feep.pbm is binary-formatted (header starts with P4, ascii-formatted starts with P1 header)
4. to convert feep.pbm to feep-ascii.pbm
   ./pbmb_to_pbma

  
