# Presentation
cd /guts/presentations/sotm/openaerialmap-2016
npm start

# Uploader Api
cd /guts/projects/oam-uploader-api
source local.env
nvm use 0.12
npm start

**Be sure to run it from port 3000**

# Uploader Api Admin
e713b5a38130875ecfadd2f4c310fadbc91a23541f1e8c7154e3d12b3034a7e0

# Uploader
cd /guts/projects/oam-uploader
npm run serve

# S3 bucket
aws s3 ls s3://hotosm-oam-staging/uploads/
aws s3 rm --recursive s3://hotosm-oam-staging/uploads/date
