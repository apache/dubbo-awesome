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
# Warmup Iteration   1: 4.872 ops/ms
# Warmup Iteration   2: 11.914 ops/ms
# Warmup Iteration   3: 12.423 ops/ms
Iteration   1: 12.662 ops/ms
Iteration   2: 12.741 ops/ms
Iteration   3: 12.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.741 ±(99.9%) 1.444 ops/ms [Average]
  (min, avg, max) = (12.662, 12.741, 12.820), stdev = 0.079
  CI (99.9%): [11.297, 14.185] (assumes normal distribution)


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
# Warmup Iteration   1: 7.926 ops/ms
# Warmup Iteration   2: 12.876 ops/ms
# Warmup Iteration   3: 12.962 ops/ms
Iteration   1: 13.002 ops/ms
Iteration   2: 13.093 ops/ms
Iteration   3: 12.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.995 ±(99.9%) 1.859 ops/ms [Average]
  (min, avg, max) = (12.890, 12.995, 13.093), stdev = 0.102
  CI (99.9%): [11.136, 14.854] (assumes normal distribution)


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
# Warmup Iteration   1: 7.564 ops/ms
# Warmup Iteration   2: 12.535 ops/ms
# Warmup Iteration   3: 12.719 ops/ms
Iteration   1: 12.797 ops/ms
Iteration   2: 12.867 ops/ms
Iteration   3: 12.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.812 ±(99.9%) 0.901 ops/ms [Average]
  (min, avg, max) = (12.772, 12.812, 12.867), stdev = 0.049
  CI (99.9%): [11.911, 13.713] (assumes normal distribution)


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
# Warmup Iteration   1: 6.739 ops/ms
# Warmup Iteration   2: 10.361 ops/ms
# Warmup Iteration   3: 10.576 ops/ms
Iteration   1: 10.554 ops/ms
Iteration   2: 10.463 ops/ms
Iteration   3: 10.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.511 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (10.463, 10.511, 10.554), stdev = 0.046
  CI (99.9%): [9.674, 11.348] (assumes normal distribution)


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.520 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.511 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (2.503, 2.511, 2.520), stdev = 0.009
  CI (99.9%): [2.350, 2.672] (assumes normal distribution)


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
# Warmup Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.525 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.503 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (2.481, 2.503, 2.525), stdev = 0.022
  CI (99.9%): [2.098, 2.907] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.919 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
Iteration   3: 2.471 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.482 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (2.471, 2.482, 2.493), stdev = 0.011
  CI (99.9%): [2.280, 2.684] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.795 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.006 ms/op
Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
Iteration   3: 3.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.010 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (3.002, 3.010, 3.014), stdev = 0.007
  CI (99.9%): [2.888, 3.131] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.169 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.092 ms/op
                 createUser·p0.999:  10.515 ms/op
                 createUser·p0.9999: 13.905 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  9.991 ms/op
                 createUser·p0.9999: 12.212 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  7.176 ms/op
                 createUser·p0.9999: 11.116 ms/op
                 createUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376975
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 177930 
    [ 2.500,  3.750) = 193663 
    [ 3.750,  5.000) = 4002 
    [ 5.000,  6.250) = 845 
    [ 6.250,  7.500) = 125 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      7.407 ms/op
     p(99.9900) =     13.342 ms/op
     p(99.9990) =     14.609 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 3.691 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  5.813 ms/op
                 existUser·p0.9999: 13.651 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   2: 2.472 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.954 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  7.058 ms/op
                 existUser·p0.9999: 23.988 ms/op
                 existUser·p1.00:   24.936 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  6.876 ms/op
                 existUser·p0.9999: 13.124 ms/op
                 existUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388478
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 192200 
    [ 2.500,  5.000) = 195603 
    [ 5.000,  7.500) = 322 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.650 ms/op
     p(99.9000) =      5.923 ms/op
     p(99.9900) =     13.955 ms/op
     p(99.9990) =     24.589 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.006 ms/op
Iteration   1: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  8.058 ms/op
                 getUser·p0.9999: 13.526 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  10.388 ms/op
                 getUser·p0.9999: 13.122 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.048 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.921 ms/op
                 getUser·p0.999:  8.540 ms/op
                 getUser·p0.9999: 11.177 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386074
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 191812 
    [ 2.500,  3.750) = 190104 
    [ 3.750,  5.000) = 3170 
    [ 5.000,  6.250) = 470 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 132 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.576 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     13.868 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 4.749 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.010 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 11.311 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.961 ms/op
                 listUser·p0.9999: 13.442 ms/op
                 listUser·p1.00:   14.615 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.575 ms/op
                 listUser·p0.9999: 13.699 ms/op
                 listUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318296
  mean =      3.013 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 92370 
    [ 2.500,  3.750) = 186830 
    [ 3.750,  5.000) = 31482 
    [ 5.000,  6.250) = 6029 
    [ 6.250,  7.500) = 799 
    [ 7.500,  8.750) = 208 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     13.176 ms/op
     p(99.9990) =     14.434 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.741 ± 1.444  ops/ms
ClientPb.existUser                       thrpt       3  12.995 ± 1.859  ops/ms
ClientPb.getUser                         thrpt       3  12.812 ± 0.901  ops/ms
ClientPb.listUser                        thrpt       3  10.511 ± 0.837  ops/ms
ClientPb.createUser                       avgt       3   2.511 ± 0.161   ms/op
ClientPb.existUser                        avgt       3   2.503 ± 0.404   ms/op
ClientPb.getUser                          avgt       3   2.482 ± 0.202   ms/op
ClientPb.listUser                         avgt       3   3.010 ± 0.121   ms/op
ClientPb.createUser                     sample  376975   2.544 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.644           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.407           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.342           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.696           ms/op
ClientPb.existUser                      sample  388478   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.872           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.923           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.955           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.936           ms/op
ClientPb.getUser                        sample  386074   2.484 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.900           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.576           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.304           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.025           ms/op
ClientPb.listUser                       sample  318296   3.013 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.807           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.176           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.615           ms/op
