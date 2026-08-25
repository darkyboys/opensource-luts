# Open Source LUTs For Everyone!
Hi, This is **Tanishq Pal**, The creator of the luts you will find in this repository. 
I personally made these luts for everyone else who is not using kdenlive to color grade their videos, Because i only uses kdenlive to color grade my footages , Edit my video and basically full production with a lot of ease.  But the problem was that i have open sourced all of the effect stacks i have ever used but it's only for kdenlive So the people using resolve, premier pro or any other software which supports luts can't directly use them. Which is why i made these luts to help others to get similar looks (If not the same).

The Source code of each lut is stored in the **.json** file, And is intended to be used with the [xlut.gen-web](https://github.com/darkyboys/xlut.gen-web)

 > Note: These are both technical and creative luts.

## Structure
 - All the **LUTs** having **GTG LOOK LUT** Prefix are the creative LUTs , Rest are Technical LUTs and should be used with caution
 - Always remember that the creative LUTs might need some technical LUTs to look as intended and Technical LUTs shouldn't be used for the final output, be sure to use something with them unless you really like the look of the footage made with them.
 - The technical LUTs can be used with any creative LUT, they are not limited to the LUTs of this repository only. They are only used to navigate a creative lut to achieve a particular look.

## Some critically important LUTs
These are super important and can be used before any other lut of modification on the image.
 - **GTG Channel Separator LUT.cube**: This is a technical LUT Which saturates the different color HUEs in a specific way that clearly separates the RED and BLUE Colors globally in the entire image, Note that this lut will oversaturate the image overall so do not panic as this is a technical lut and should be used as a post processing step instead of the final output.
 - **GTG Channel Cooler.cube**:  This lut actually cools the blue and green colors even more (Must be usedd after GTG Channel Separator LUT.cube, Or it can look absolutely terrible and destroy the skin tones) and warms the Warm Hues even more, Essentially giving the entire image a nice color contrast which can be used to create pretty much any other look with any other creative lut,) Be careful with this lut as this will not decrease the saturation on it's own, Either decrease the saturation yourself or use a creative lut to do that.
 - **GTG GTG Color Correction LUT (RED Manager V1/V2).cube**: This lut corrects the huge amount of REDs in the shadows region using the channel curves. (Be careful as this can make the footage's shadows unnaturally cyan)

> Note: These luts can be used to navigate a creative lut for cold vs warm color grading, When you apply these you will have red hue controlling your skin tones and the sun light and basically any warm color in the image whereas the rest of the image will turn towards teal / cyan / blue which can be usedd to manipulate the rest of the image).

## Feel free to pair the technical luts with almost any other creative lut that you want.
## Thanks for reading!
Have a nice time.
