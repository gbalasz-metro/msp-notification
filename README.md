# msp-notification
MSP notification action

### Usage

```
      - name: MSP Notification
        id: msp-notification
        uses: gbalasz-metro/msp-notification@v1.0
        with:
          status: started
          version: 1.1
          pipeline: pipeline-name
          event: ${{ github.event }}
```
