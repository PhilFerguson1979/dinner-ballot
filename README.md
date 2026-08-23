# Two-Week Dinner Ballot

A static family voting page. Everyone taps what they'd be happy to eat over the
next two weeks; the tally sorts by how much of the family wants each meal and
builds the fortnight from the winners. Every meal carries its recipe.

No accounts and no backend. Each person's picks are stored on their own phone and
travel back as a short share code that gets pasted into the tally.

Generated from JSON, not hand-edited. To change anything, edit the data in
`../data/` and re-run `python build_site.py` from the parent folder.
