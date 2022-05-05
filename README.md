# -hImage2
SDL_BlitSurface($hImage1, 0, $pScreen, 0) _SDL_FreeSurface($hImage1) $hImage2 = _SDL_GDIPlus_ImageLoadFromFile($sFile2) _SDL_BlitSurface($hImage2, 0, $pScreen, 0)
