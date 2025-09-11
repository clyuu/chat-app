# `invoice 03.pdf` සඳහා සම්පූර්ණ විශ්ලේෂණ වාර්තාව

## 1. ස්වයංක්‍රීය සාරාංශය (Automated Summary)
- **ඉන්වොයිස් අංකය**: INV-3337
- **ඉන්වොයිස් දිනය**: සොයාගත නොහැකි විය
- **ගෙවිය යුතු මුළු මුදල**: $93.50
- **ගෙවීම් කොන්දේසි**: සොයාගත නොහැකි විය

--- 
## 2. Textract මගින් සොයාගත් සම්පූර්ණ දත්ත (Raw Data)

### Layout Elements
**Other:**
- 
- 
- 

### Form Fields (Key-Value Pairs)
| Key | Value |
| --- | --- |
| Rate/Price | $85.00 |
| Page | 1/1 |
| BSB # | 4321 432 |
| Sub Total | $85.00 |
| To: | Test Business 123 Somewhere St Melbourne, VIC 3000 test@test.com |
| ACC # | 1234 1234 |
| Service | Web Design This is a sample description. |
| Hrs/Qty | 1.00 |
| From: | DEMO Sliced Invoices Suite 5A-1204 123 Somewhere Street Your City AZ 12345 admin@slicedinvoices.com |
| Adjust | 0.00% |
| Total | $93.50 |
| Thanks for choosing DEMO - | Sliced Invoices I admin@slicedinvoices.com |
| Tax | $8.50 |
| Invoice Number | INV-3337 |
| Due Date | January 31, 2016 |
| Invoice Date | January 25, 2016 |
| Sub Total | $85.00 |
| Total Due | $93.50 |
| Order Number | 12345 |

### Tables
**වගුව 1:**
| Invoice Number | INV-3337 |
| Order Number | 12345 |
| Invoice Date | January 25, 2016 |
| Due Date | January 31, 2016 |
| Total Due | $93.50 |

**වගුව 2:**
| Hrs/Qty | Service | Rate/Price | Adjust | Sub Total |
| 1.00 | Web Design This is a sample description. | $85.00 | 0.00% | $85.00 |

**වගුව 3:**
| Sub Total | $85.00 |
| Tax | $8.50 |
| Total | $93.50 |

### Query Results
- **Q:** N/A
- **A:** $93.50 (Confidence: 94.00%)
- **Q:** N/A
- **A:** Payment is due within 30 days from date of invoice. Late payment is subject to fees of 5% per month. (Confidence: 68.00%)
- **Q:** N/A
- **A:** January 25, 2016 (Confidence: 99.00%)
- **Q:** N/A
- **A:** INV-3337 (Confidence: 97.00%)
