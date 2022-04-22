* Fixes a false negative where the `in_rescue?` check would bypass situations where the return was inside a transaction but ouside of a rescue
