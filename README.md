# location
Android设备GPS信息读取
gps = new GpsManager.Builder(getApplication()).setProvider("test").setMinTime(5).setMinDistance(5).setLocationListener(this).setNmeaListener(this).builder();
        gps.start();
