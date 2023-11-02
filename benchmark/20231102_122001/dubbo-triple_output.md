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
# Warmup Iteration   1: 4.198 ops/ms
# Warmup Iteration   2: 11.725 ops/ms
# Warmup Iteration   3: 12.121 ops/ms
Iteration   1: 12.496 ops/ms
Iteration   2: 12.336 ops/ms
Iteration   3: 12.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.437 ±(99.9%) 1.602 ops/ms [Average]
  (min, avg, max) = (12.336, 12.437, 12.496), stdev = 0.088
  CI (99.9%): [10.835, 14.039] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.398 ops/ms
# Warmup Iteration   2: 12.762 ops/ms
# Warmup Iteration   3: 12.846 ops/ms
Iteration   1: 12.674 ops/ms
Iteration   2: 12.919 ops/ms
Iteration   3: 12.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.811 ±(99.9%) 2.282 ops/ms [Average]
  (min, avg, max) = (12.674, 12.811, 12.919), stdev = 0.125
  CI (99.9%): [10.529, 15.093] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.444 ops/ms
# Warmup Iteration   2: 12.553 ops/ms
# Warmup Iteration   3: 12.777 ops/ms
Iteration   1: 12.816 ops/ms
Iteration   2: 12.747 ops/ms
Iteration   3: 12.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.747 ±(99.9%) 1.266 ops/ms [Average]
  (min, avg, max) = (12.677, 12.747, 12.816), stdev = 0.069
  CI (99.9%): [11.480, 14.013] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.421 ops/ms
# Warmup Iteration   2: 10.454 ops/ms
# Warmup Iteration   3: 10.497 ops/ms
Iteration   1: 10.648 ops/ms
Iteration   2: 10.667 ops/ms
Iteration   3: 10.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.645 ±(99.9%) 0.439 ops/ms [Average]
  (min, avg, max) = (10.620, 10.645, 10.667), stdev = 0.024
  CI (99.9%): [10.206, 11.084] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.206 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.003 ms/op
Iteration   1: 2.522 ±(99.9%) 0.004 ms/op
Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
Iteration   3: 2.539 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (2.522, 2.541, 2.563), stdev = 0.021
  CI (99.9%): [2.160, 2.923] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.963 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.464 ±(99.9%) 0.003 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.461 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (2.457, 2.461, 2.464), stdev = 0.004
  CI (99.9%): [2.392, 2.530] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.003 ms/op
Iteration   1: 2.520 ±(99.9%) 0.005 ms/op
Iteration   2: 2.511 ±(99.9%) 0.003 ms/op
Iteration   3: 2.534 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.511, 2.521, 2.534), stdev = 0.012
  CI (99.9%): [2.311, 2.732] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.125 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.004 ms/op
Iteration   1: 3.048 ±(99.9%) 0.005 ms/op
Iteration   2: 3.024 ±(99.9%) 0.005 ms/op
Iteration   3: 3.012 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.028 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (3.012, 3.028, 3.048), stdev = 0.018
  CI (99.9%): [2.696, 3.360] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.240 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.688 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.562 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  12.646 ms/op
                 createUser·p0.9999: 14.352 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  10.125 ms/op
                 createUser·p0.9999: 12.411 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  8.487 ms/op
                 createUser·p0.9999: 10.247 ms/op
                 createUser·p1.00:   10.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375424
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 179813 
    [ 2.500,  3.750) = 190599 
    [ 3.750,  5.000) = 3920 
    [ 5.000,  6.250) = 551 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.656 ms/op
                 existUser·p0.999:  5.479 ms/op
                 existUser·p0.9999: 14.435 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  8.990 ms/op
                 existUser·p0.9999: 13.697 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  8.768 ms/op
                 existUser·p0.9999: 15.008 ms/op
                 existUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386489
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 190044 
    [ 2.500,  3.750) = 191277 
    [ 3.750,  5.000) = 3871 
    [ 5.000,  6.250) = 777 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      7.108 ms/op
     p(99.9900) =     14.380 ms/op
     p(99.9990) =     15.848 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.026 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.969 ms/op
                 getUser·p0.999:  12.708 ms/op
                 getUser·p0.9999: 14.877 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.281 ms/op
                 getUser·p0.999:  10.118 ms/op
                 getUser·p0.9999: 16.561 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.051 ms/op
                 getUser·p0.999:  8.110 ms/op
                 getUser·p0.9999: 11.632 ms/op
                 getUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377195
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 184115 
    [ 2.500,  3.750) = 186965 
    [ 3.750,  5.000) = 4692 
    [ 5.000,  6.250) = 872 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 92 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =      8.668 ms/op
     p(99.9900) =     15.041 ms/op
     p(99.9990) =     17.434 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.959 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.009 ms/op
Iteration   1: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.667 ms/op
                 listUser·p0.999:  9.066 ms/op
                 listUser·p0.9999: 10.804 ms/op
                 listUser·p1.00:   12.173 ms/op

Iteration   2: 3.040 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.804 ms/op
                 listUser·p0.999:  10.600 ms/op
                 listUser·p0.9999: 12.960 ms/op
                 listUser·p1.00:   13.763 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.411 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 10.976 ms/op
                 listUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318324
  mean =      3.013 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 91341 
    [ 2.500,  3.750) = 187284 
    [ 3.750,  5.000) = 32315 
    [ 5.000,  6.250) = 5771 
    [ 6.250,  7.500) = 792 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 289 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     12.340 ms/op
     p(99.9990) =     13.604 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.437 ± 1.602  ops/ms
ClientPb.existUser                       thrpt       3  12.811 ± 2.282  ops/ms
ClientPb.getUser                         thrpt       3  12.747 ± 1.266  ops/ms
ClientPb.listUser                        thrpt       3  10.645 ± 0.439  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.381   ms/op
ClientPb.existUser                        avgt       3   2.461 ± 0.069   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.210   ms/op
ClientPb.listUser                         avgt       3   3.028 ± 0.332   ms/op
ClientPb.createUser                     sample  375424   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.793           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.175           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.025           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.877           ms/op
ClientPb.existUser                      sample  386489   2.482 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.740           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.108           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.380           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.991           ms/op
ClientPb.getUser                        sample  377195   2.542 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.824           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.668           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.041           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.924           ms/op
ClientPb.listUser                       sample  318324   3.013 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.915           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.340           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.763           ms/op
