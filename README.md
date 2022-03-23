# MyReactNative

        scripts:
        - name: Check
          script: |
              if [ -z ${FCI_TAG} ]
              then
                echo "Not a tag build"
              else
                echo "$FCI_TAG"
              fi
