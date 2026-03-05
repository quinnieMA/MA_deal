## Deal multiple ##
#### ** Deal Information**
| Original Pattern | Standardized Output |
|-----------------|---------------------|
| Deal Number | `deal_num` |
| Acquiror name | `acq_name` |
| Target name | `tar_name` |
| Vendor name | `ven_name` |

#### **Value Multiples (Pre-deal & Post-deal)**
| Multiple Type | Pre-deal Output | Post-deal Output |
|--------------|-----------------|------------------|
| Operating Revenue/Turnover | `pre_rev_mul` | `post_rev_mul` |
| EBITDA | `pre_ebitda_mul` | `post_ebitda_mul` |
| EBIT | `pre_ebit_mul` | `post_ebit_mul` |
| Profit Before Tax | `pre_pbt_mul` | `post_pbt_mul` |
| Profit After Tax | `pre_pat_mul` | `post_pat_mul` |
| Net Profit | `pre_np_mul` | `post_np_mul` |
| Total Assets | `pre_ta_mul` | `post_ta_mul` |
| Net Assets | `pre_na_mul` | `post_na_mul` |
| Current Liabilities | `pre_cl_mul` | `post_cl_mul` |
| Shareholders Funds | `pre_eq_mul` | `post_eq_mul` |
| Market Capitalisation | `pre_cap_mul` | `post_cap_mul` |

#### **Year Suffix Handling**
| Year Pattern | Suffix |
|--------------|--------|
| Last avail. yr | `_ly` |
| First avail. yr | `_fy` |
| Year - 1 | `_y1` |
| Year - 2 | `_y2` |

## Deal structure_date ##
#### **Deal Information**
| Original Pattern | Standardized Output |
|-----------------|---------------------|
| Unnamed: 0 | `unnamed_0` |
| Deal Number | `deal_num` |
| Deal type | `deal_type` |
| Deal structure | `deal_struct` |
| Deal financing | `deal_fin` |
| Deal method of payment | `deal_pay_method` |
| Deal method of payment value th USD | `deal_pay_method_val_usd` |
| Deal status | `deal_status` |

#### **Date Fields**
| Original Pattern | Standardized Output |
|-----------------|---------------------|
| Rumour date | `rumour_d` |
| Announced date | `announced_d` |
| Expected completion date | `expected_comp_d` |
| Assumed completion date | `assumed_comp_d` |
| Completed date | `completed_d` |
| Postponed date | `postponed_d` |
| Withdrawn date | `withdrawn_d` |
| Last deal status date | `last_deal_status_d` |
| Last deal value, offer price, bid premium update date | `last_deal_val_up_d` |
| Last deal status update date | `last_deal_status_up_d` |
| Last % of stake update date | `last_pct_stake_up_d` |
| Last acquiror, target, vendor update date | `last_acq_tar_ven_up_d` |
| Last advisor update date | `last_advisor_up_d` |
| Last deal comment, rationale update date | `last_comment_up_d` |
| Last update | `last_up` |

#### **Year Fields** (Derived from Dates)
| Original Pattern | Standardized Output |
|-----------------|---------------------|
| rumour_date_year | `rumour_d_yr` |
| announced_date_year | `announced_d_yr` |
| expected_completion_date_year | `expected_comp_d_yr` |
| assumed_completion_date_year | `assumed_comp_d_yr` |
| completed_date_year | `completed_d_yr` |
| postponed_date_year | `postponed_d_yr` |
| withdrawn_date_year | `withdrawn_d_yr` |
| last_deal_status_date_year | `last_deal_status_d_yr` |
| last_deal_value_offer_price_bid_premium_update_date_year | `last_deal_val_up_d_yr` |
| last_deal_status_update_date_year | `last_deal_status_up_d_yr` |
| last_pct_of_stake_update_date_year | `last_pct_stake_up_d_yr` |
| last_acquiror_target_vendor_update_date_year | `last_acq_tar_ven_up_d_yr` |
| last_advisor_update_date_year | `last_advisor_up_d_yr` |
| last_deal_comment_rationale_update_date_year | `last_comment_up_d_yr` |
| last_update_year | `last_up_yr` |

### 3. **Suffix Extraction Patterns**
| Pattern | Suffix | Description |
|---------|--------|-------------|
| Last avail. yr | `_ly` | Last available year |
| Year - 1 | `_y1` | One year prior |
| Year - 2 | `_y2` | Two years prior |
| th USD | `_usd` | Thousand USD |
| 1st avail | `_1st` | First available |
