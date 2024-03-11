# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.762 ops/ms
# Warmup Iteration   2: 12.129 ops/ms
# Warmup Iteration   3: 12.645 ops/ms
Iteration   1: 12.860 ops/ms
Iteration   2: 12.903 ops/ms
Iteration   3: 12.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.867 ±(99.9%) 0.595 ops/ms [Average]
  (min, avg, max) = (12.839, 12.867, 12.903), stdev = 0.033
  CI (99.9%): [12.272, 13.462] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.717 ops/ms
# Warmup Iteration   2: 13.238 ops/ms
# Warmup Iteration   3: 13.165 ops/ms
Iteration   1: 13.309 ops/ms
Iteration   2: 13.119 ops/ms
Iteration   3: 13.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.267 ±(99.9%) 2.394 ops/ms [Average]
  (min, avg, max) = (13.119, 13.267, 13.371), stdev = 0.131
  CI (99.9%): [10.873, 15.660] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.637 ops/ms
# Warmup Iteration   2: 12.812 ops/ms
# Warmup Iteration   3: 12.957 ops/ms
Iteration   1: 13.123 ops/ms
Iteration   2: 13.034 ops/ms
Iteration   3: 12.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.038 ±(99.9%) 1.494 ops/ms [Average]
  (min, avg, max) = (12.959, 13.038, 13.123), stdev = 0.082
  CI (99.9%): [11.544, 14.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.782 ops/ms
# Warmup Iteration   2: 10.611 ops/ms
# Warmup Iteration   3: 10.777 ops/ms
Iteration   1: 10.808 ops/ms
Iteration   2: 10.761 ops/ms
Iteration   3: 10.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.784 ±(99.9%) 0.425 ops/ms [Average]
  (min, avg, max) = (10.761, 10.784, 10.808), stdev = 0.023
  CI (99.9%): [10.359, 11.208] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.003 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.498 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.487, 2.498, 2.506), stdev = 0.010
  CI (99.9%): [2.315, 2.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.594 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.393 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.371 ±(99.9%) 0.003 ms/op
Iteration   1: 2.388 ±(99.9%) 0.004 ms/op
Iteration   2: 2.373 ±(99.9%) 0.003 ms/op
Iteration   3: 2.424 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.395 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (2.373, 2.395, 2.424), stdev = 0.026
  CI (99.9%): [1.918, 2.872] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.934 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
Iteration   3: 2.450 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.471 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (2.450, 2.471, 2.500), stdev = 0.026
  CI (99.9%): [1.999, 2.943] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.599 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
Iteration   3: 2.961 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.969 ±(99.9%) 0.132 ms/op [Average]
  (min, avg, max) = (2.961, 2.969, 2.976), stdev = 0.007
  CI (99.9%): [2.836, 3.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.657 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  10.559 ms/op
                 createUser·p0.9999: 13.910 ms/op
                 createUser·p1.00:   14.631 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  9.578 ms/op
                 createUser·p0.9999: 12.648 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  8.750 ms/op
                 createUser·p0.9999: 13.189 ms/op
                 createUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384989
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 188278 
    [ 2.500,  3.750) = 192368 
    [ 3.750,  5.000) = 3512 
    [ 5.000,  6.250) = 291 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      8.749 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     14.565 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.526 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.436 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.393 ±(99.9%) 0.005 ms/op
Iteration   1: 2.397 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  7.902 ms/op
                 existUser·p0.9999: 13.233 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   2: 2.392 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  6.032 ms/op
                 existUser·p0.9999: 11.791 ms/op
                 existUser·p1.00:   12.354 ms/op

Iteration   3: 2.379 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.871 ms/op
                 existUser·p0.95:   2.961 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  7.311 ms/op
                 existUser·p0.9999: 14.094 ms/op
                 existUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401367
  mean =      2.389 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 203962 
    [ 2.500,  3.750) = 194913 
    [ 3.750,  5.000) = 1716 
    [ 5.000,  6.250) = 278 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      3.482 ms/op
     p(99.9000) =      6.608 ms/op
     p(99.9900) =     13.534 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.958 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  6.711 ms/op
                 getUser·p0.9999: 14.615 ms/op
                 getUser·p1.00:   15.860 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.982 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  7.426 ms/op
                 getUser·p0.9999: 13.466 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.622 ms/op
                 getUser·p0.999:  6.039 ms/op
                 getUser·p0.9999: 11.729 ms/op
                 getUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389085
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 195751 
    [ 2.500,  3.750) = 189275 
    [ 3.750,  5.000) = 3227 
    [ 5.000,  6.250) = 330 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      6.745 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     15.409 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.008 ms/op
Iteration   1: 2.939 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.793 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 11.049 ms/op
                 listUser·p1.00:   12.468 ms/op

Iteration   2: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  8.997 ms/op
                 listUser·p0.9999: 10.378 ms/op
                 listUser·p1.00:   10.682 ms/op

Iteration   3: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  8.814 ms/op
                 listUser·p0.9999: 10.774 ms/op
                 listUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324706
  mean =      2.954 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 103179 
    [ 2.500,  3.750) = 184115 
    [ 3.750,  5.000) = 30760 
    [ 5.000,  6.250) = 5349 
    [ 6.250,  7.500) = 539 
    [ 7.500,  8.750) = 233 
    [ 8.750, 10.000) = 268 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     10.707 ms/op
     p(99.9990) =     11.596 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.867 ± 0.595  ops/ms
ClientPb.existUser                       thrpt       3  13.267 ± 2.394  ops/ms
ClientPb.getUser                         thrpt       3  13.038 ± 1.494  ops/ms
ClientPb.listUser                        thrpt       3  10.784 ± 0.425  ops/ms
ClientPb.createUser                       avgt       3   2.498 ± 0.183   ms/op
ClientPb.existUser                        avgt       3   2.395 ± 0.477   ms/op
ClientPb.getUser                          avgt       3   2.471 ± 0.472   ms/op
ClientPb.listUser                         avgt       3   2.969 ± 0.132   ms/op
ClientPb.createUser                     sample  384989   2.492 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.844           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.631           ms/op
ClientPb.existUser                      sample  401367   2.389 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.949           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.896           ms/op
ClientPb.existUser:existUser·p0.95      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.608           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.534           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.090           ms/op
ClientPb.getUser                        sample  389085   2.465 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.947           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.745           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.517           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.860           ms/op
ClientPb.listUser                       sample  324706   2.954 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.816           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.978           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.707           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.468           ms/op
