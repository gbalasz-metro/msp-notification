# msp-notification
MSP notification action

### Usage

```
      - name: MSP Notification
        id: msp-notification
        uses: gbalasz-metro/msp-notification@v0.3
        with:
          status: started
          version: 1.1
          pipeline: pipeline-name
          user: ${{ github.event.head_commit.author.name }}
```
