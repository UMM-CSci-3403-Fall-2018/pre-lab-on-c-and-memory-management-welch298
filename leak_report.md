# Leak report

Memory that was allocated by calloc by is_clean was never freed. So the fix is
to free this memory.
