def quicksort(eip):
    if len(eip) <= 1:
        return eip
    eip_in = eip[len(eip) // 2]
    mlblr_in = [x for x in eip if x < eip_in]
    mlblr = [x for x in eip if x == eip_in]
    mlblr_out = [x for x in eip if x > eip_in]
    return quicksort(mlblr_in) + mlblr + quicksort(mlblr_out)

print(quicksort([3,6,8,10,1,2,1]))
# Prints "[1, 1, 2, 3, 6, 8, 10]"
