# QuickSearch UMD-Fork

This repository is a forked version of the NSCU QuickSearch repository,
incorporating UMD-specific changes.

## Changes to NCSU QuickSearch functionality

### Best Bets do not fade out

Modified "app/assets/javascripts/quick_search/quicksearch.js" so that
the Best Bets label remains displayed, instead of fading out after a few
seconds.

### Native search interface link is included in JSON results

Modified "app/controllers/quick_search/search_controller.rb" so that
the link to the native search interface, including query parameters, is
included in the JSON result.

### No results link is included in JSON results

Modified "app/controllers/quick_search/search_controller.rb" so that
the "no_results_link" for the search is included in the JSON result.
