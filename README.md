# L1Table
Latex table for L1 Phase-II

The notebook `L1Table.ipynb` should take care of everything, just pass the name of the `.csv` that contains the menu in the third cell.

The notebook should run out of the box with the current status of the menu and the files produced by the Phase-II tools.

Just note that for it to run smoothly you should rename the columns of the `csv` as:

    L1Path,counts,eff,rate,null

also, the last three rows of the `csv` should be (note that the naming is important, especially `total menu`):

    total menu, COUNTS, EFF, RATE
    total raw, COUNTS, EFF, RATE (just copy the row above, probably this is not even needed but better safe than sorry)
    total,TOTAL COUNTS, (same as above, probably I never use this, but better safe than sorry)

`onl2off_th_update.th`: define here the seeds and the corresponding online/offline thresholds for each leg.

Define in the `l1_names_map` dictionary the name of the seeds and the description you want it to have in the table, together with the additional requirements and the plateau efficiency.
