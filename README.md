443\_homework\_1
================

``` r
x <-read.table("DC19.txt", header = TRUE, sep = ",", stringsAsFactors = FALSE)
y <- head(x[, 1:15], n = 10)
print.data.frame(y)
```

    ##    STATE_CODE_001 STRUCTURE_NUMBER_008 RECORD_TYPE_005A ROUTE_PREFIX_005B
    ## 1              11      0001                           1                 5
    ## 2              11      0002                           1                 5
    ## 3              11      0003                           1                 5
    ## 4              11      0004                           1                 5
    ## 5              11      0005                           1                 5
    ## 6              11      0006                           1                 5
    ## 7              11      0007                           1                 2
    ## 8              11      0007(EAST RAMP)                1                 2
    ## 9              11      0010                           1                 2
    ## 10             11      0011                           1                 5
    ##    SERVICE_LEVEL_005C ROUTE_NUMBER_005D DIRECTION_005E HIGHWAY_DISTRICT_002
    ## 1                   1             00000              0                    1
    ## 2                   1             00000              0                    1
    ## 3                   1             00000              0                    1
    ## 4                   1             00000              0                    1
    ## 5                   1             00000              0                    1
    ## 6                   1             00000              0                    1
    ## 7                   1             00029              0                    1
    ## 8                   7             00029              0                    1
    ## 9                   1             00000              0                    1
    ## 10                  1             00000              0                    1
    ##    COUNTY_CODE_003 PLACE_CODE_004      FEATURES_DESC_006A
    ## 1                1              0        POTOMAC R. & C&O
    ## 2                1              0           C&amp;O CANAL
    ## 3                1              0           C&amp;O CANAL
    ## 4                1              0           C&amp;O CANAL
    ## 5                1              0           C&amp;O CANAL
    ## 6                1              0           C&amp;O CANAL
    ## 7                1              0         WHITEHURST FRWY
    ## 8                1              0 STORAGE YD NEAR POTOMAC
    ## 9                1              0   VIRGINIA AVENUE  N.W.
    ## 10               1              0    SOUTH CAPITOL STREET
    ##    CRITICAL_FACILITY_006B FACILITY_CARRIED_007              LOCATION_009
    ## 1                      NA         CHAIN BRIDGE  OVER POTOMAC RIVER  N.W.
    ## 2                      NA     WISCONSIN AVENUE  GEORGETOWN &amp; C&amp;O
    ## 3                      NA     31ST STREET N.W.  GEORGETOWN &amp; C&amp;O
    ## 4                      NA   JEFFERSON ST  N.W.  GEORGETOWN &amp; C&amp;O
    ## 5                      NA    30TH STREET  N.W.  GEORGETOWN &amp; C&amp;O
    ## 6                      NA    29TH STREET  N.W.  GEORGETOWN &amp; C&amp;O
    ## 7                      NA           Key Bridge           WHITEHURST FRWY
    ## 8                      NA    E RAMP TO WH FRWY KEY BRIDGE OVER POTOMAC R
    ## 9                      NA    23RD STREET  N.W.    VA. AVE. OVER 23RD ST.
    ## 10                     NA       M STREET  S.W. M STREET &amp; S. CAPITOL
    ##    MIN_VERT_CLR_010
    ## 1             99.99
    ## 2             99.99
    ## 3             99.99
    ## 4             99.99
    ## 5             99.99
    ## 6             99.99
    ## 7             99.99
    ## 8             99.99
    ## 9             99.99
    ## 10            99.99
