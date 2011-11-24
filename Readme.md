# Usage

    // do not overwrite if file exists
    $this->Zip->create($pathToZipFile, $arrayOfFileLocations, false);

    // overwrite if file exists
    $this->Zip->create($pathToZipFile, $arrayOfFileLocations, true);