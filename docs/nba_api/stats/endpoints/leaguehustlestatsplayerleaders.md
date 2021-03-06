# LeagueHustleStatsPlayerLeaders
##### [nba_api/stats/endpoints/leaguehustlestatsplayerleaders.py](https://github.com/swar/nba_api/blob/master/nba_api/stats/endpoints/leaguehustlestatsplayerleaders.py)

##### Endpoint URL
>[https://stats.nba.com/stats/leaguehustlestatsplayerleaders](https://stats.nba.com/stats/leaguehustlestatsplayerleaders)

##### Valid URL
>[https://stats.nba.com/stats/leaguehustlestatsplayerleaders?College=&Conference=&Country=&DateFrom=&DateTo=&Division=&DraftPick=&DraftYear=&Height=&LeagueID=&Location=&Month=&OpponentTeamID=&Outcome=&PORound=&PerMode=Totals&PlayerExperience=&PlayerPosition=&Season=2019-20&SeasonSegment=&SeasonType=Regular+Season&TeamID=&VsConference=&VsDivision=&Weight=](https://stats.nba.com/stats/leaguehustlestatsplayerleaders?College=&Conference=&Country=&DateFrom=&DateTo=&Division=&DraftPick=&DraftYear=&Height=&LeagueID=&Location=&Month=&OpponentTeamID=&Outcome=&PORound=&PerMode=Totals&PlayerExperience=&PlayerPosition=&Season=2019-20&SeasonSegment=&SeasonType=Regular+Season&TeamID=&VsConference=&VsDivision=&Weight=)

## Parameters
API Parameter Name | Python Parameter Variable | Pattern | Required | Nullable
------------ | ------------ | :-----------: | :---: | :---:
[_**PerMode**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#PerMode) | per_mode_time | `^(Totals)\|(PerGame)\|(Per48)\|(Per40)\|(Per36)\|(PerMinute)$` | `Y` |  | 
[_**Season**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#Season) | season |  | `Y` |  | 
[_**SeasonType**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#SeasonType) | season_type_all_star | `^(Regular Season)\|(Pre Season)\|(Playoffs)\|(All Star)$` | `Y` |  | 
[_**Weight**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#Weight) | weight_nullable |  |  | `Y` | 
[_**VsDivision**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#VsDivision) | vs_division_nullable |  |  | `Y` | 
[_**VsConference**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#VsConference) | vs_conference_nullable |  |  | `Y` | 
[_**TeamID**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#TeamID) | team_id_nullable |  |  | `Y` | 
[_**SeasonSegment**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#SeasonSegment) | season_segment_nullable |  |  | `Y` | 
[_**PlayerPosition**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#PlayerPosition) | player_position_nullable |  |  | `Y` | 
[_**PlayerExperience**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#PlayerExperience) | player_experience_nullable |  |  | `Y` | 
[_**PORound**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#PORound) | po_round_nullable |  |  | `Y` | 
[_**Outcome**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#Outcome) | outcome_nullable |  |  | `Y` | 
[_**OpponentTeamID**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#OpponentTeamID) | opponent_team_id_nullable |  |  | `Y` | 
[_**Month**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#Month) | month_nullable |  |  | `Y` | 
[_**Location**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#Location) | location_nullable |  |  | `Y` | 
[_**LeagueID**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#LeagueID) | league_id_nullable |  | `Y` | `Y` | 
[_**Height**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#Height) | height_nullable |  |  | `Y` | 
[_**DraftYear**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#DraftYear) | draft_year_nullable |  |  | `Y` | 
[_**DraftPick**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#DraftPick) | draft_pick_nullable |  |  | `Y` | 
[_**Division**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#Division) | division_simple_nullable |  |  | `Y` | 
[_**DateTo**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#DateTo) | date_to_nullable |  |  | `Y` | 
[_**DateFrom**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#DateFrom) | date_from_nullable |  |  | `Y` | 
[_**Country**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#Country) | country_nullable |  |  | `Y` | 
[_**Conference**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#Conference) | conference_nullable |  |  | `Y` | 
[_**College**_](https://github.com/swar/nba_api/blob/master/docs/nba_api/stats/library/parameters.md#College) | college_nullable |  |  | `Y` | 

## Data Sets
#### PlayerChargesDrawnLeaders `player_charges_drawn_leaders`
```text
['PLAYER_ID', 'PLAYER_NAME', 'TEAM_ID', 'TEAM_ABBREVIATION', 'AGE', 'RANK', 'CHARGES_DRAWN']
```

#### PlayerContestedShotsLeaders `player_contested_shots_leaders`
```text
['PLAYER_ID', 'PLAYER_NAME', 'TEAM_ID', 'TEAM_ABBREVIATION', 'AGE', 'RANK', 'CONTESTED_SHOTS']
```

#### PlayerDeflectionsLeaders `player_deflections_leaders`
```text
['PLAYER_ID', 'PLAYER_NAME', 'TEAM_ID', 'TEAM_ABBREVIATION', 'AGE', 'RANK', 'DEFLECTIONS']
```

#### PlayerLooseBallLeaders `player_loose_ball_leaders`
```text
['PLAYER_ID', 'PLAYER_NAME', 'TEAM_ID', 'TEAM_ABBREVIATION', 'AGE', 'RANK', 'LOOSE_BALLS_RECOVERED']
```

#### PlayerScreenAssistLeaders `player_screen_assist_leaders`
```text
['PLAYER_ID', 'PLAYER_NAME', 'TEAM_ID', 'TEAM_ABBREVIATION', 'AGE', 'RANK', 'SCREEN_ASSISTS']
```

#### Table5 `table5`
```text
['PLAYER_ID', 'PLAYER_NAME', 'TEAM_ID', 'TEAM_ABBREVIATION', 'AGE', 'RANK', 'BOX_OUTS']
```


## JSON
```json
{
    "data_sets": {
        "PlayerChargesDrawnLeaders": [
            "PLAYER_ID",
            "PLAYER_NAME",
            "TEAM_ID",
            "TEAM_ABBREVIATION",
            "AGE",
            "RANK",
            "CHARGES_DRAWN"
        ],
        "PlayerContestedShotsLeaders": [
            "PLAYER_ID",
            "PLAYER_NAME",
            "TEAM_ID",
            "TEAM_ABBREVIATION",
            "AGE",
            "RANK",
            "CONTESTED_SHOTS"
        ],
        "PlayerDeflectionsLeaders": [
            "PLAYER_ID",
            "PLAYER_NAME",
            "TEAM_ID",
            "TEAM_ABBREVIATION",
            "AGE",
            "RANK",
            "DEFLECTIONS"
        ],
        "PlayerLooseBallLeaders": [
            "PLAYER_ID",
            "PLAYER_NAME",
            "TEAM_ID",
            "TEAM_ABBREVIATION",
            "AGE",
            "RANK",
            "LOOSE_BALLS_RECOVERED"
        ],
        "PlayerScreenAssistLeaders": [
            "PLAYER_ID",
            "PLAYER_NAME",
            "TEAM_ID",
            "TEAM_ABBREVIATION",
            "AGE",
            "RANK",
            "SCREEN_ASSISTS"
        ],
        "Table5": [
            "PLAYER_ID",
            "PLAYER_NAME",
            "TEAM_ID",
            "TEAM_ABBREVIATION",
            "AGE",
            "RANK",
            "BOX_OUTS"
        ]
    },
    "endpoint": "LeagueHustleStatsPlayerLeaders",
    "last_validated_date": "2020-08-15",
    "nullable_parameters": [
        "College",
        "Conference",
        "Country",
        "DateFrom",
        "DateTo",
        "Division",
        "DraftPick",
        "DraftYear",
        "Height",
        "LeagueID",
        "Location",
        "Month",
        "OpponentTeamID",
        "Outcome",
        "PORound",
        "PlayerExperience",
        "PlayerPosition",
        "SeasonSegment",
        "TeamID",
        "VsConference",
        "VsDivision",
        "Weight"
    ],
    "parameter_patterns": {
        "College": null,
        "Conference": null,
        "Country": null,
        "DateFrom": null,
        "DateTo": null,
        "Division": null,
        "DraftPick": null,
        "DraftYear": null,
        "Height": null,
        "LeagueID": null,
        "Location": null,
        "Month": null,
        "OpponentTeamID": null,
        "Outcome": null,
        "PORound": null,
        "PerMode": "^(Totals)|(PerGame)|(Per48)|(Per40)|(Per36)|(PerMinute)$",
        "PlayerExperience": null,
        "PlayerPosition": null,
        "Season": null,
        "SeasonSegment": null,
        "SeasonType": "^(Regular Season)|(Pre Season)|(Playoffs)|(All Star)$",
        "TeamID": null,
        "VsConference": null,
        "VsDivision": null,
        "Weight": null
    },
    "parameters": [
        "College",
        "Conference",
        "Country",
        "DateFrom",
        "DateTo",
        "Division",
        "DraftPick",
        "DraftYear",
        "Height",
        "LeagueID",
        "Location",
        "Month",
        "OpponentTeamID",
        "Outcome",
        "PORound",
        "PerMode",
        "PlayerExperience",
        "PlayerPosition",
        "Season",
        "SeasonSegment",
        "SeasonType",
        "TeamID",
        "VsConference",
        "VsDivision",
        "Weight"
    ],
    "required_parameters": [
        "LeagueID",
        "PerMode",
        "Season",
        "SeasonType"
    ],
    "status": "success"
}
```

Last validated 2020-08-16