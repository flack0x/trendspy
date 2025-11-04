# Complete Google Trends Options Reference

**Last Updated**: November 2025
**Purpose**: Comprehensive list of ALL available filter options for Google Trends

---

## Table of Contents
1. [Time Periods](#time-periods)
2. [Countries (Geo Locations)](#countries-geo-locations)
3. [US States & Regions](#us-states--regions)
4. [Categories](#categories)
5. [Sort Options](#sort-options)
6. [Trend Status](#trend-status)

---

## Time Periods

### Available Options (4 total)

| Display Name | Hours Value | URL Parameter | Script Argument |
|--------------|-------------|---------------|-----------------|
| **Past 4 hours** | 4 | `hours=4` | `--hours 4` |
| **Past 24 hours** *(default)* | 24 | `hours=24` | `--hours 24` |
| **Past 48 hours** | 48 | `hours=48` | `--hours 48` |
| **Past 7 days** | 168 | `hours=168` | `--hours 168` |

### Usage Examples
```bash
# Past 4 hours (breaking trends)
--hours 4

# Past 24 hours (default, daily summary)
--hours 24

# Past 7 days (weekly overview)
--hours 168
```

---

## Countries (Geo Locations)

### Total Count: **114 Countries**

### All Available Countries (Alphabetical)

| Country | Code | Has Sub-Regions? |
|---------|------|------------------|
| Albania | AL | No |
| Algeria | DZ | No |
| Angola | AO | No |
| Argentina | AR | Yes ⭐ |
| Armenia | AM | No |
| Australia | AU | Yes ⭐ |
| Austria | AT | Yes ⭐ |
| Azerbaijan | AZ | No |
| Bahrain | BH | No |
| Bangladesh | BD | No |
| Belarus | BY | No |
| Belgium | BE | Yes ⭐ |
| Benin | BJ | No |
| Bolivia | BO | No |
| Bosnia & Herzegovina | BA | No |
| Brazil | BR | Yes ⭐ |
| Bulgaria | BG | No |
| Burkina Faso | BF | No |
| Cambodia | KH | No |
| Cameroon | CM | No |
| Canada | CA | Yes ⭐ |
| Chile | CL | Yes ⭐ |
| Colombia | CO | Yes ⭐ |
| Congo - Kinshasa | CD | No |
| Costa Rica | CR | No |
| Côte d'Ivoire | CI | No |
| Croatia | HR | No |
| Cuba | CU | No |
| Cyprus | CY | No |
| Czechia | CZ | No |
| Denmark | DK | Yes ⭐ |
| Dominican Republic | DO | No |
| Ecuador | EC | Yes ⭐ |
| Egypt | EG | Yes ⭐ |
| El Salvador | SV | No |
| Estonia | EE | No |
| Ethiopia | ET | No |
| Finland | FI | No |
| France | FR | Yes ⭐ |
| Georgia | GE | No |
| Germany | DE | Yes ⭐ |
| Ghana | GH | No |
| Greece | GR | No |
| Guatemala | GT | No |
| Haiti | HT | No |
| Honduras | HN | No |
| Hong Kong | HK | No |
| Hungary | HU | No |
| India | IN | Yes ⭐ |
| Indonesia | ID | Yes ⭐ |
| Iran | IR | No |
| Iraq | IQ | No |
| Ireland | IE | No |
| Israel | IL | Yes ⭐ |
| Italy | IT | Yes ⭐ |
| Jamaica | JM | No |
| Japan | JP | Yes ⭐ |
| Jordan | JO | No |
| Kazakhstan | KZ | No |
| Kenya | KE | No |
| Kuwait | KW | No |
| Kyrgyzstan | KG | No |
| Latvia | LV | No |
| Lebanon | LB | No |
| Libya | LY | No |
| Lithuania | LT | No |
| Malaysia | MY | Yes ⭐ |
| Mali | ML | No |
| Mexico | MX | Yes ⭐ |
| Moldova | MD | No |
| Morocco | MA | No |
| Mozambique | MZ | No |
| Myanmar (Burma) | MM | No |
| Nepal | NP | No |
| Netherlands | NL | Yes ⭐ |
| New Zealand | NZ | Yes ⭐ |
| Nicaragua | NI | No |
| Nigeria | NG | Yes ⭐ |
| North Macedonia | MK | No |
| Norway | NO | No |
| Oman | OM | No |
| Pakistan | PK | Yes ⭐ |
| Palestine | PS | No |
| Panama | PA | No |
| Paraguay | PY | No |
| Peru | PE | Yes ⭐ |
| Philippines | PH | Yes ⭐ |
| Poland | PL | Yes ⭐ |
| Portugal | PT | Yes ⭐ |
| Puerto Rico | PR | No |
| Qatar | QA | No |
| Romania | RO | No |
| Russia | RU | Yes ⭐ |
| Saudi Arabia | SA | Yes ⭐ |
| Senegal | SN | No |
| Serbia | RS | No |
| Singapore | SG | No |
| Slovakia | SK | No |
| Slovenia | SI | No |
| South Africa | ZA | Yes ⭐ |
| South Korea | KR | Yes ⭐ |
| Spain | ES | Yes ⭐ |
| Sri Lanka | LK | No |
| Sweden | SE | Yes ⭐ |
| Switzerland | CH | Yes ⭐ |
| Syria | SY | No |
| Taiwan | TW | Yes ⭐ |
| Tanzania | TZ | No |
| Thailand | TH | No |
| Trinidad & Tobago | TT | No |
| Tunisia | TN | No |
| Türkiye | TR | Yes ⭐ |
| Turkmenistan | TM | No |
| Uganda | UG | No |
| Ukraine | UA | Yes ⭐ |
| United Arab Emirates | AE | Yes ⭐ |
| United Kingdom | GB | Yes ⭐ |
| **United States** | **US** | **Yes ⭐⭐ (Full Details Below)** |
| Uruguay | UY | Yes ⭐ |
| Uzbekistan | UZ | No |
| Venezuela | VE | No |
| Vietnam | VN | Yes ⭐ |
| Yemen | YE | No |
| Zambia | ZM | No |
| Zimbabwe | ZW | No |

**⭐ = Has sub-regions (states/provinces/regions)**

### Popular Countries (Quick Reference)

```bash
# North America
--geo US    # United States (+ 50 states)
--geo CA    # Canada
--geo MX    # Mexico

# Europe
--geo GB    # United Kingdom
--geo DE    # Germany
--geo FR    # France
--geo IT    # Italy
--geo ES    # Spain

# Asia
--geo IN    # India
--geo JP    # Japan
--geo CN    # China
--geo KR    # South Korea

# Oceania
--geo AU    # Australia
--geo NZ    # New Zealand

# South America
--geo BR    # Brazil
--geo AR    # Argentina

# Middle East
--geo SA    # Saudi Arabia
--geo AE    # United Arab Emirates
```

---

## US States & Regions

### United States Sub-Regions (52 total)

When selecting United States, you can drill down to:
- **51 States + DC**
- **By DMA** (Designated Market Area) option available

#### All 50 States + DC

| State Name | Code* | State Name | Code* |
|-----------|-------|-----------|-------|
| Alabama | US-AL | Montana | US-MT |
| Alaska | US-AK | Nebraska | US-NE |
| Arizona | US-AZ | Nevada | US-NV |
| Arkansas | US-AR | New Hampshire | US-NH |
| California | US-CA | New Jersey | US-NJ |
| Colorado | US-CO | New Mexico | US-NM |
| Connecticut | US-CT | New York | US-NY |
| Delaware | US-DE | North Carolina | US-NC |
| **District of Columbia** | US-DC | North Dakota | US-ND |
| Florida | US-FL | Ohio | US-OH |
| Georgia | US-GA | Oklahoma | US-OK |
| Hawaii | US-HI | Oregon | US-OR |
| Idaho | US-ID | Pennsylvania | US-PA |
| Illinois | US-IL | Rhode Island | US-RI |
| Indiana | US-IN | South Carolina | US-SC |
| Iowa | US-IA | South Dakota | US-SD |
| Kansas | US-KS | Tennessee | US-TN |
| Kentucky | US-KY | Texas | US-TX |
| Louisiana | US-LA | Utah | US-UT |
| Maine | US-ME | Vermont | US-VT |
| Maryland | US-MD | Virginia | US-VA |
| Massachusetts | US-MA | Washington | US-WA |
| Michigan | US-MI | West Virginia | US-WV |
| Minnesota | US-MN | Wisconsin | US-WI |
| Mississippi | US-MS | Wyoming | US-WY |
| Missouri | US-MO | | |

*Note: State codes follow ISO 3166-2 format (US-XX)

#### Usage Examples
```bash
# California trends
--geo US-CA

# New York trends
--geo US-NY

# Texas trends
--geo US-TX

# All United States (no specific state)
--geo US
```

### Other Countries with Sub-Regions

**Note**: The following countries also have regional breakdowns:

- **Canada**: Provinces (AB, BC, MB, NB, NL, NS, NT, NU, ON, PE, QC, SK, YT)
- **United Kingdom**: England, Scotland, Wales, Northern Ireland
- **Germany**: States (Bayern, Berlin, etc.)
- **Australia**: States (NSW, VIC, QLD, WA, SA, TAS, ACT, NT)
- **India**: States (Maharashtra, Delhi, Karnataka, etc.)
- **Brazil**: States (São Paulo, Rio de Janeiro, etc.)
- **And 30+ more countries!**

*For a complete list of sub-regions for each country, you would need to click through each one on the Google Trends interface.*

---

## Categories

### Total Count: **20 Categories**

| Category Name | Code | Trend Count (Approximate) |
|---------------|------|---------------------------|
| **All categories** *(default)* | `all` or `` (empty) | 600+ |
| Autos and Vehicles | `autos` | Variable |
| Beauty and Fashion | `beauty` | Variable |
| Business and Finance | `business` | Variable |
| Climate | `climate` | Variable |
| Entertainment | `entertainment` | 80-100 |
| Food and Drink | `food` | Variable |
| Games | `games` | Variable |
| Health | `health` | Variable |
| Hobbies and Leisure | `hobbies` | Variable |
| Jobs and Education | `jobs` | Variable |
| Law and Government | `law` | Variable |
| Other | `other` | Variable |
| Pets and Animals | `pets` | Variable |
| Politics | `politics` | Variable |
| Science | `science` | Variable |
| Shopping | `shopping` | Variable |
| Sports | `sports` | 400+ |
| Technology | `technology` | Variable |
| Travel and Transportation | `travel` | Variable |

### Usage Examples
```bash
# All categories (default)
--category all

# Sports only (very popular)
--category sports

# Technology trends
--category technology

# Entertainment (movies, TV, celebrities)
--category entertainment

# Business & Finance
--category business
```

---

## Sort Options

### Total Count: **4 Sort Options**

| Sort Option | Code | Description |
|-------------|------|-------------|
| **Relevance** *(default)* | `relevance` | Google's algorithm (most relevant trends) |
| Title | `title` | Alphabetical order (A-Z) |
| Search Volume | `volume` | Highest search volume first |
| Recency | `recency` | Most recent trends first |

### Usage Examples
```bash
# Default relevance
--sort relevance

# Highest volume trends first
--sort volume

# Newest trends first
--sort recency

# Alphabetical
--sort title
```

---

## Trend Status

### Total Count: **2 Options**

| Option | Description | Flag |
|--------|-------------|------|
| **All trends** *(default)* | Shows both active and ended trends | (no flag) |
| **Active trends only** | Shows only currently trending (still rising) | `--active-only` |

### Usage Examples
```bash
# All trends (default)
# (no flag needed)

# Only active/rising trends
--active-only
```

---

## Quick Reference Card

### Complete Parameter Combinations

```bash
# Minimal (all defaults)
py download_trends_configurable.py

# Specify everything
py download_trends_configurable.py \
    --geo US \
    --hours 24 \
    --category all \
    --sort relevance

# US State-specific
py download_trends_configurable.py --geo US-CA --hours 4 --category technology

# International with filters
py download_trends_configurable.py --geo JP --category entertainment --sort volume

# Active trends only
py download_trends_configurable.py --geo UK --active-only --sort recency
```

---

## Summary Statistics

| Option Type | Total Count |
|-------------|-------------|
| **Time Periods** | 4 |
| **Countries** | 114 |
| **US States + DC** | 51 |
| **Categories** | 20 |
| **Sort Options** | 4 |
| **Trend Status** | 2 |
| **Total Combinations** | 188,000+ |

---

## Notes

1. **Sub-Regions**: 42 countries have sub-regional breakdowns (states, provinces, regions)
2. **DMA Support**: United States offers "By DMA" (Designated Market Area) view
3. **URL Parameters**: Can use `geo=XX` for countries, `geo=XX-YY` for regions
4. **Updates**: Google rarely changes these core options
5. **Category Counts**: Vary by location and time period
6. **Empty Categories**: Some location/time combinations may have no trends for certain categories

---

## How to List Options in Script

Add these flags to the configurable downloader:

```bash
# List all available locations
py download_trends_configurable.py --list-locations

# List all categories
py download_trends_configurable.py --list-categories

# List all time periods
py download_trends_configurable.py --list-times

# Show all options
py download_trends_configurable.py --help
```

*(Implementation coming soon)*

---

**Last verified**: November 2025
