# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.900 ops/ms
# Warmup Iteration   2: 11.871 ops/ms
# Warmup Iteration   3: 12.091 ops/ms
Iteration   1: 12.257 ops/ms
Iteration   2: 12.342 ops/ms
Iteration   3: 12.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.362 ±(99.9%) 2.116 ops/ms [Average]
  (min, avg, max) = (12.257, 12.362, 12.486), stdev = 0.116
  CI (99.9%): [10.245, 14.478] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.164 ops/ms
# Warmup Iteration   2: 12.876 ops/ms
# Warmup Iteration   3: 12.822 ops/ms
Iteration   1: 12.774 ops/ms
Iteration   2: 13.024 ops/ms
Iteration   3: 12.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.902 ±(99.9%) 2.280 ops/ms [Average]
  (min, avg, max) = (12.774, 12.902, 13.024), stdev = 0.125
  CI (99.9%): [10.623, 15.182] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.521 ops/ms
# Warmup Iteration   2: 12.330 ops/ms
# Warmup Iteration   3: 12.428 ops/ms
Iteration   1: 12.742 ops/ms
Iteration   2: 12.717 ops/ms
Iteration   3: 12.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.751 ±(99.9%) 0.713 ops/ms [Average]
  (min, avg, max) = (12.717, 12.751, 12.794), stdev = 0.039
  CI (99.9%): [12.038, 13.464] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.594 ops/ms
# Warmup Iteration   2: 10.571 ops/ms
# Warmup Iteration   3: 10.488 ops/ms
Iteration   1: 10.609 ops/ms
Iteration   2: 10.557 ops/ms
Iteration   3: 10.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.598 ±(99.9%) 0.677 ops/ms [Average]
  (min, avg, max) = (10.557, 10.598, 10.628), stdev = 0.037
  CI (99.9%): [9.921, 11.275] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.944 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.630 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.004 ms/op
Iteration   1: 2.547 ±(99.9%) 0.005 ms/op
Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
Iteration   3: 2.524 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (2.524, 2.549, 2.577), stdev = 0.027
  CI (99.9%): [2.063, 3.036] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.476 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.462, 2.476, 2.488), stdev = 0.013
  CI (99.9%): [2.237, 2.714] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.003 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (2.483, 2.501, 2.523), stdev = 0.020
  CI (99.9%): [2.134, 2.869] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.806 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.005 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
Iteration   2: 3.056 ±(99.9%) 0.005 ms/op
Iteration   3: 3.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.043 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (3.037, 3.043, 3.056), stdev = 0.011
  CI (99.9%): [2.841, 3.245] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.249 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.717 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.006 ms/op
Iteration   1: 2.570 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  11.701 ms/op
                 createUser·p0.9999: 14.405 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   2: 2.580 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  9.538 ms/op
                 createUser·p0.9999: 12.144 ms/op
                 createUser·p1.00:   12.517 ms/op

Iteration   3: 2.593 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  8.954 ms/op
                 createUser·p0.9999: 11.321 ms/op
                 createUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371508
  mean =      2.581 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 176098 
    [ 2.500,  3.750) = 190627 
    [ 3.750,  5.000) = 3874 
    [ 5.000,  6.250) = 406 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 130 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.899 ms/op
     p(99.9000) =      9.429 ms/op
     p(99.9900) =     13.608 ms/op
     p(99.9990) =     14.794 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.722 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.348 ms/op
                 existUser·p0.9999: 13.664 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  7.315 ms/op
                 existUser·p0.9999: 12.926 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  9.349 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389877
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 192769 
    [ 2.500,  3.750) = 193571 
    [ 3.750,  5.000) = 2714 
    [ 5.000,  6.250) = 314 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      8.253 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     14.135 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.006 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  5.382 ms/op
                 getUser·p0.9999: 13.538 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  9.810 ms/op
                 getUser·p0.9999: 14.080 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 12.050 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379713
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 186472 
    [ 2.500,  3.750) = 187902 
    [ 3.750,  5.000) = 4249 
    [ 5.000,  6.250) = 637 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      6.185 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     14.425 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.793 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.009 ms/op
Iteration   1: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.634 ms/op
                 listUser·p0.9999: 10.584 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   2: 3.062 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 12.599 ms/op
                 listUser·p1.00:   13.976 ms/op

Iteration   3: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  10.007 ms/op
                 listUser·p0.9999: 11.715 ms/op
                 listUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315998
  mean =      3.036 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 84816 
    [ 2.500,  3.750) = 190926 
    [ 3.750,  5.000) = 33200 
    [ 5.000,  6.250) = 5572 
    [ 6.250,  7.500) = 704 
    [ 7.500,  8.750) = 261 
    [ 8.750, 10.000) = 191 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     12.000 ms/op
     p(99.9990) =     13.458 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.362 ± 2.116  ops/ms
ClientPb.existUser                       thrpt       3  12.902 ± 2.280  ops/ms
ClientPb.getUser                         thrpt       3  12.751 ± 0.713  ops/ms
ClientPb.listUser                        thrpt       3  10.598 ± 0.677  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.487   ms/op
ClientPb.existUser                        avgt       3   2.476 ± 0.239   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.367   ms/op
ClientPb.listUser                         avgt       3   3.043 ± 0.202   ms/op
ClientPb.createUser                     sample  371508   2.581 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.932           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.658           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.429           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.608           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.860           ms/op
ClientPb.existUser                      sample  389877   2.460 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.019           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.253           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.042           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.713           ms/op
ClientPb.getUser                        sample  379713   2.526 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.850           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.185           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.844           ms/op
ClientPb.listUser                       sample  315998   3.036 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.000           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.976           ms/op
