# Statement Template Examples

The following example statements are provided for your convenience and conform to the video profile requirements.

## Initialized

```
{
    "actor": {
        "mbox": "mailto:jlh@example.com",
        "name": "Video User",
        "objectType": "Agent"
    },
    "verb": {
        "id": "http://adlnet.gov/expapi/verbs/initialized",
        "display": {
            "en-US": "initialized"
        }
    },
    "timestamp": "2018-08-07T15:27:52.365Z",
    "object": {
        "definition": {
            "type": "https://w3id.org/xapi/video/activity-type/video",
            "name": {
                "en-US": "Ocean Life"
            },
            "description": {
                "en-US": "A short video clip of ocean lifeforms, used by videojs.com as part of their demo."
            }
        },
        "id": "http://vjs.zencdn.net/v/oceans.mp4",
        "objectType": "Activity"
    },
    "context": {
        "contextActivities": {
            "category": [
                {
                    "id": "https://w3id.org/xapi/video"
                }
            ]
        },
        "extensions": {
            "https://w3id.org/xapi/video/extensions/volume": 1,
            "https://w3id.org/xapi/video/extensions/video-playback-size": "640x264",
            "https://w3id.org/xapi/video/extensions/user-agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_12_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/68.0.3440.84 Safari/537.36",
            "https://w3id.org/xapi/video/extensions/speed": "1x",
            "https://w3id.org/xapi/video/extensions/cc-subtitle-lang": "",
            "https://w3id.org/xapi/video/extensions/completion-threshold": "1.0",
            "https://w3id.org/xapi/video/extensions/session-id": "86c5b148-4462-4da9-a13f-b570c27fa049",
            "https://w3id.org/xapi/video/extensions/length": 46.613333,
            "https://w3id.org/xapi/video/extensions/quality": "960x400",
            "https://w3id.org/xapi/video/extensions/screen-size": "2560x1440",
            "https://w3id.org/xapi/video/extensions/frame-rate": "23.98",
            "https://w3id.org/xapi/video/extensions/cc-enabled": false,
            "https://w3id.org/xapi/video/extensions/full-screen": false
        },
        "registration": "96094a33-cc66-4d9a-8810-a0850ae2a4e1"
    },
    "id": "86c5b148-4462-4da9-a13f-b570c27fa049"
}
```

## Played

```
{
    "actor": {
        "mbox": "mailto:jlh@example.com",
        "name": "Video User",
        "objectType": "Agent"
    },
    "verb": {
        "id": "https://w3id.org/xapi/video/verbs/played",
        "display": {
            "en-US": "played"
        }
    },
    "timestamp": "2018-08-07T15:27:52.376Z",
    "object": {
        "definition": {
            "type": "https://w3id.org/xapi/video/activity-type/video",
            "name": {
                "en-US": "Ocean Life"
            },
            "description": {
                "en-US": "A short video clip of ocean lifeforms, used by videojs.com as part of their demo."
            }
        },
        "id": "http://vjs.zencdn.net/v/oceans.mp4",
        "objectType": "Activity"
    },
    "result": {
        "extensions": {
            "https://w3id.org/xapi/video/extensions/time": 0
        }
    },
    "context": {
        "contextActivities": {
            "category": [
                {
                    "id": "https://w3id.org/xapi/video"
                }
            ]
        },
        "extensions": {
            "https://w3id.org/xapi/video/extensions/session-id": "86c5b148-4462-4da9-a13f-b570c27fa049",
            "https://w3id.org/xapi/video/extensions/length": 46.613333
        },
        "registration": "96094a33-cc66-4d9a-8810-a0850ae2a4e1"
    },
    "id": "ac522d8a-ed56-4a5e-bc86-14067aec4101"
}
```

## Paused

```
{
    "actor": {
        "mbox": "mailto:jlh@example.com",
        "name": "Video User",
        "objectType": "Agent"
    },
    "verb": {
        "id": "https://w3id.org/xapi/video/verbs/paused",
        "display": {
            "en-US": "paused"
        }
    },
    "timestamp": "2018-08-07T15:27:55.273Z",
    "object": {
        "definition": {
            "type": "https://w3id.org/xapi/video/activity-type/video",
            "name": {
                "en-US": "Ocean Life"
            },
            "description": {
                "en-US": "A short video clip of ocean lifeforms, used by videojs.com as part of their demo."
            }
        },
        "id": "http://vjs.zencdn.net/v/oceans.mp4",
        "objectType": "Activity"
    },
    "result": {
        "extensions": {
            "https://w3id.org/xapi/video/extensions/played-segments": "0[.]2.997",
            "https://w3id.org/xapi/video/extensions/progress": 0.06,
            "https://w3id.org/xapi/video/extensions/time": 2.997
        }
    },
    "context": {
        "contextActivities": {
            "category": [
                {
                    "id": "https://w3id.org/xapi/video"
                }
            ]
        },
        "extensions": {
            "https://w3id.org/xapi/video/extensions/session-id": "86c5b148-4462-4da9-a13f-b570c27fa049",
            "https://w3id.org/xapi/video/extensions/length": 46.613333
        },
        "registration": "96094a33-cc66-4d9a-8810-a0850ae2a4e1"
    },
    "id": "587c8e19-3a5e-4be2-ba09-9c6b68c4fb20"
}
```

## Seeked \(Change Video Playback from 4.473 Seconds to 1.9 Seconds \)

```
{
    "actor": {
        "mbox": "mailto:jlh@example.com",
        "name": "Video User",
        "objectType": "Agent"
    },
    "verb": {
        "id": "https://w3id.org/xapi/video/verbs/seeked",
        "display": {
            "en-US": "seeked"
        }
    },
    "timestamp": "2018-08-07T15:37:53.491Z",
    "object": {
        "definition": {
            "type": "https://w3id.org/xapi/video/activity-type/video",
            "name": {
                "en-US": "Ocean Life"
            },
            "description": {
                "en-US": "A short video clip of ocean lifeforms, used by videojs.com as part of their demo."
            }
        },
        "id": "http://vjs.zencdn.net/v/oceans.mp4",
        "objectType": "Activity"
    },
    "result": {
        "extensions": {
            "https://w3id.org/xapi/video/extensions/time-to": 1.9,
            "https://w3id.org/xapi/video/extensions/time-from": 4.473
        }
    },
    "context": {
        "contextActivities": {
            "category": [
                {
                    "id": "https://w3id.org/xapi/video"
                }
            ]
        },
        "extensions": {
            "https://w3id.org/xapi/video/extensions/session-id": "86c5b148-4462-4da9-a13f-b570c27fa049"
        },
        "registration": "96094a33-cc66-4d9a-8810-a0850ae2a4e1"
    },
    "id": "4183175b-a6b0-4e59-8614-fd9c0d2593dd"
}
```

## Interacted Event \(Change to Full Screen\)

```
{
    "actor": {
        "mbox": "mailto:jlh@example.com",
        "name": "Video User",
        "objectType": "Agent"
    },
    "verb": {
        "id": "http://adlnet.gov/expapi/verbs/interacted",
        "display": {
            "en-US": "interacted"
        }
    },
    "timestamp": "2018-08-07T15:41:59.549Z",
    "object": {
        "definition": {
            "type": "https://w3id.org/xapi/video/activity-type/video",
            "name": {
                "en-US": "Ocean Life"
            },
            "description": {
                "en-US": "A short video clip of ocean lifeforms, used by videojs.com as part of their demo."
            }
        },
        "id": "http://vjs.zencdn.net/v/oceans.mp4",
        "objectType": "Activity"
    },
    "result": {
        "extensions": {
            "https://w3id.org/xapi/video/extensions/time": 10.096
        }
    },
    "context": {
        "contextActivities": {
            "category": [
                {
                    "id": "https://w3id.org/xapi/video"
                }
            ]
        },
        "extensions": {
            "https://w3id.org/xapi/video/extensions/session-id": "86c5b148-4462-4da9-a13f-b570c27fa049",
            "https://w3id.org/xapi/video/extensions/video-playback-size": "1122x1177",
            "https://w3id.org/xapi/video/extensions/screen-size": "2560x1440",
            "https://w3id.org/xapi/video/extensions/full-screen": true
        },
        "registration": "96094a33-cc66-4d9a-8810-a0850ae2a4e1"
    },
    "id": "abe55d73-ffb3-4093-ab1a-424592c119ee"
}
```

## Interacted Event \(Change Back to Original Screen Size\)

```
{
    "actor": {
        "mbox": "mailto:jlh@example.com",
        "name": "Video User",
        "objectType": "Agent"
    },
    "verb": {
        "id": "http://adlnet.gov/expapi/verbs/interacted",
        "display": {
            "en-US": "interacted"
        }
    },
    "timestamp": "2018-08-07T15:42:03.400Z",
    "object": {
        "definition": {
            "type": "https://w3id.org/xapi/video/activity-type/video",
            "name": {
                "en-US": "Ocean Life"
            },
            "description": {
                "en-US": "A short video clip of ocean lifeforms, used by videojs.com as part of their demo."
            }
        },
        "id": "http://vjs.zencdn.net/v/oceans.mp4",
        "objectType": "Activity"
    },
    "result": {
        "extensions": {
            "https://w3id.org/xapi/video/extensions/time": 13.947
        }
    },
    "context": {
        "contextActivities": {
            "category": [
                {
                    "id": "https://w3id.org/xapi/video"
                }
            ]
        },
        "extensions": {
            "https://w3id.org/xapi/video/extensions/session-id": "86c5b148-4462-4da9-a13f-b570c27fa049",
            "https://w3id.org/xapi/video/extensions/video-playback-size": "640x264",
            "https://w3id.org/xapi/video/extensions/screen-size": "2560x1440",
            "https://w3id.org/xapi/video/extensions/full-screen": false
        },
        "registration": "96094a33-cc66-4d9a-8810-a0850ae2a4e1"
    },
    "id": "c3371384-4598-43f2-b1b3-86be5df66ed5"
}
```

## Interacted Event \(Change Volume to Muted\)

```
{
    "actor": {
        "mbox": "mailto:jlh@example.com",
        "name": "Video User",
        "objectType": "Agent"
    },
    "verb": {
        "id": "http://adlnet.gov/expapi/verbs/interacted",
        "display": {
            "en-US": "interacted"
        }
    },
    "timestamp": "2018-08-07T15:42:12.016Z",
    "object": {
        "definition": {
            "type": "https://w3id.org/xapi/video/activity-type/video",
            "name": {
                "en-US": "Ocean Life"
            },
            "description": {
                "en-US": "A short video clip of ocean lifeforms, used by videojs.com as part of their demo."
            }
        },
        "id": "http://vjs.zencdn.net/v/oceans.mp4",
        "objectType": "Activity"
    },
    "result": {
        "extensions": {
            "https://w3id.org/xapi/video/extensions/time": 20.536
        }
    },
    "context": {
        "contextActivities": {
            "category": [
                {
                    "id": "https://w3id.org/xapi/video"
                }
            ]
        },
        "extensions": {
            "https://w3id.org/xapi/video/extensions/volume": 0,
            "https://w3id.org/xapi/video/extensions/session-id": "86c5b148-4462-4da9-a13f-b570c27fa049"
        },
        "registration": "96094a33-cc66-4d9a-8810-a0850ae2a4e1"
    },
    "id": "eb6ca563-1e61-4776-a5b0-2a23be8e43b0"
}
```

## Interacted Event \(Change Volume to Unmuted\)

```
{
    "actor": {
        "mbox": "mailto:jlh@example.com",
        "name": "Video User",
        "objectType": "Agent"
    },
    "verb": {
        "id": "http://adlnet.gov/expapi/verbs/interacted",
        "display": {
            "en-US": "interacted"
        }
    },
    "timestamp": "2018-08-07T15:42:15.443Z",
    "object": {
        "definition": {
            "type": "https://w3id.org/xapi/video/activity-type/video",
            "name": {
                "en-US": "Ocean Life"
            },
            "description": {
                "en-US": "A short video clip of ocean lifeforms, used by videojs.com as part of their demo."
            }
        },
        "id": "http://vjs.zencdn.net/v/oceans.mp4",
        "objectType": "Activity"
    },
    "result": {
        "extensions": {
            "https://w3id.org/xapi/video/extensions/time": 24.036
        }
    },
    "context": {
        "contextActivities": {
            "category": [
                {
                    "id": "https://w3id.org/xapi/video"
                }
            ]
        },
        "extensions": {
            "https://w3id.org/xapi/video/extensions/volume": 1,
            "https://w3id.org/xapi/video/extensions/session-id": "86c5b148-4462-4da9-a13f-b570c27fa049"
        },
        "registration": "96094a33-cc66-4d9a-8810-a0850ae2a4e1"
    },
    "id": "f48f70b2-505e-46ae-a562-19fcae19f2ae"
}
```

## Interacted \(Enabled Closed Captioning\)

```
{
    "actor": {
        "mbox": "mailto:jlh@example.com",
        "name": "Video User",
        "objectType": "Agent"
    },
    "verb": {
        "id": "http://adlnet.gov/expapi/verbs/interacted",
        "display": {
            "en-US": "interacted"
        }
    },
    "timestamp": "2018-08-07T15:42:20.066Z",
    "object": {
        "definition": {
            "type": "https://w3id.org/xapi/video/activity-type/video",
            "name": {
                "en-US": "Ocean Life"
            },
            "description": {
                "en-US": "A short video clip of ocean lifeforms, used by videojs.com as part of their demo."
            }
        },
        "id": "http://vjs.zencdn.net/v/oceans.mp4",
        "objectType": "Activity"
    },
    "result": {
        "extensions": {
            "https://w3id.org/xapi/video/extensions/time": 28.799
        }
    },
    "context": {
        "contextActivities": {
            "category": [
                {
                    "id": "https://w3id.org/xapi/video"
                }
            ]
        },
        "extensions": {
            "https://w3id.org/xapi/video/extensions/session-id": "86c5b148-4462-4da9-a13f-b570c27fa049",
            "https://w3id.org/xapi/video/extensions/cc-subtitle-lang": "en",
            "https://w3id.org/xapi/video/extensions/cc-enabled": true
        },
        "registration": "96094a33-cc66-4d9a-8810-a0850ae2a4e1"
    },
    "id": "f71a5b62-53d5-4794-aa75-7e0dc2570eed"
}
```

## Completed

```
{
    "actor": {
        "mbox": "mailto:jlh@example.com",
        "name": "Video User",
        "objectType": "Agent"
    },
    "verb": {
        "id": "http://adlnet.gov/expapi/verbs/completed",
        "display": {
            "en-US": "completed"
        }
    },
    "timestamp": "2018-08-07T16:10:24.158Z",
    "object": {
        "definition": {
            "type": "https://w3id.org/xapi/video/activity-type/video",
            "name": {
                "en-US": "Ocean Life"
            },
            "description": {
                "en-US": "A short video clip of ocean lifeforms, used by videojs.com as part of their demo."
            }
        },
        "id": "http://vjs.zencdn.net/v/oceans.mp4",
        "objectType": "Activity"
    },
    "result": {
        "completion": true,
        "extensions": {
            "https://w3id.org/xapi/video/extensions/played-segments": "0[.]46.613",
            "https://w3id.org/xapi/video/extensions/progress": 1,
            "https://w3id.org/xapi/video/extensions/time": 46.613
        }
    },
    "context": {
        "contextActivities": {
            "category": [
                {
                    "id": "https://w3id.org/xapi/video"
                }
            ]
        },
        "extensions": {
            "https://w3id.org/xapi/video/extensions/session-id": "7a1f8a80-8b62-4cf5-9165-a4976280f6c4",
            "https://w3id.org/xapi/video/extensions/completion-threshold": "1.0",
            "https://w3id.org/xapi/video/extensions/length": 46.613333
        },
        "registration": "70ec479c-a37d-4407-89ad-9727313e71dc"
    },
    "id": "019b33ec-4426-40b7-b296-54f05cb9291e"
}
```

## Terminated

```
{
    "actor": {
        "mbox": "mailto:jlh@example.com",
        "name": "Video User",
        "objectType": "Agent"
    },
    "verb": {
        "id": "http://adlnet.gov/expapi/verbs/terminated",
        "display": {
            "en-US": "terminated"
        }
    },
    "timestamp": "2018-08-07T16:10:28.452Z",
    "object": {
        "definition": {
            "type": "https://w3id.org/xapi/video/activity-type/video",
            "name": {
                "en-US": "Ocean Life"
            },
            "description": {
                "en-US": "A short video clip of ocean lifeforms, used by videojs.com as part of their demo."
            }
        },
        "id": "http://vjs.zencdn.net/v/oceans.mp4",
        "objectType": "Activity"
    },
    "result": {
        "extensions": {
            "https://w3id.org/xapi/video/extensions/played-segments": "0[.]46.613",
            "https://w3id.org/xapi/video/extensions/progress": 1,
            "https://w3id.org/xapi/video/extensions/time": 46.613
        }
    },
    "context": {
        "contextActivities": {
            "category": [
                {
                    "id": "https://w3id.org/xapi/video"
                }
            ]
        },
        "extensions": {
            "https://w3id.org/xapi/video/extensions/session-id": "7a1f8a80-8b62-4cf5-9165-a4976280f6c4",
            "https://w3id.org/xapi/video/extensions/completion-threshold": "1.0",
            "https://w3id.org/xapi/video/extensions/length": 46.613333
        },
        "registration": "70ec479c-a37d-4407-89ad-9727313e71dc"
    },
    "id": "b3cd221b-cd2c-40cd-9291-e3fdcd1f4129"
}
```



