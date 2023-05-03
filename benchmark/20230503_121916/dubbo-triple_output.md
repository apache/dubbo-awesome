# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.267 ops/ms
# Warmup Iteration   2: 5.817 ops/ms
# Warmup Iteration   3: 8.908 ops/ms
Iteration   1: 9.543 ops/ms
Iteration   2: 9.732 ops/ms
Iteration   3: 9.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.594 ±(99.9%) 2.198 ops/ms [Average]
  (min, avg, max) = (9.508, 9.594, 9.732), stdev = 0.120
  CI (99.9%): [7.396, 11.793] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ops/ms
# Warmup Iteration   2: 8.895 ops/ms
# Warmup Iteration   3: 9.847 ops/ms
Iteration   1: 9.794 ops/ms
Iteration   2: 10.392 ops/ms
Iteration   3: 10.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.184 ±(99.9%) 6.167 ops/ms [Average]
  (min, avg, max) = (9.794, 10.184, 10.392), stdev = 0.338
  CI (99.9%): [4.017, 16.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.234 ops/ms
# Warmup Iteration   2: 8.952 ops/ms
# Warmup Iteration   3: 9.515 ops/ms
Iteration   1: 9.699 ops/ms
Iteration   2: 10.190 ops/ms
Iteration   3: 10.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.986 ±(99.9%) 4.666 ops/ms [Average]
  (min, avg, max) = (9.699, 9.986, 10.190), stdev = 0.256
  CI (99.9%): [5.319, 14.652] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.812 ops/ms
# Warmup Iteration   2: 7.692 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 8.245 ops/ms
Iteration   2: 8.277 ops/ms
Iteration   3: 8.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.335 ±(99.9%) 2.369 ops/ms [Average]
  (min, avg, max) = (8.245, 8.335, 8.484), stdev = 0.130
  CI (99.9%): [5.967, 10.704] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.350 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.005 ms/op
Iteration   1: 3.187 ±(99.9%) 0.003 ms/op
Iteration   2: 3.164 ±(99.9%) 0.006 ms/op
Iteration   3: 3.254 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.202 ±(99.9%) 0.852 ms/op [Average]
  (min, avg, max) = (3.164, 3.202, 3.254), stdev = 0.047
  CI (99.9%): [2.350, 4.053] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.621 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.003 ms/op
Iteration   1: 3.044 ±(99.9%) 0.004 ms/op
Iteration   2: 3.156 ±(99.9%) 0.006 ms/op
Iteration   3: 3.109 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.103 ±(99.9%) 1.027 ms/op [Average]
  (min, avg, max) = (3.044, 3.103, 3.156), stdev = 0.056
  CI (99.9%): [2.077, 4.130] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.817 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.002 ms/op
Iteration   1: 3.244 ±(99.9%) 0.002 ms/op
Iteration   2: 3.283 ±(99.9%) 0.005 ms/op
Iteration   3: 3.203 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.243 ±(99.9%) 0.731 ms/op [Average]
  (min, avg, max) = (3.203, 3.243, 3.283), stdev = 0.040
  CI (99.9%): [2.512, 3.974] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.495 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.007 ms/op
Iteration   1: 3.887 ±(99.9%) 0.007 ms/op
Iteration   2: 3.757 ±(99.9%) 0.006 ms/op
Iteration   3: 3.719 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.788 ±(99.9%) 1.607 ms/op [Average]
  (min, avg, max) = (3.719, 3.788, 3.887), stdev = 0.088
  CI (99.9%): [2.181, 5.394] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.517 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.009 ms/op
Iteration   1: 3.352 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  14.854 ms/op
                 createUser·p0.9999: 17.760 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   2: 3.328 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.692 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 21.280 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   3: 3.295 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.267 ms/op
                 createUser·p0.999:  15.196 ms/op
                 createUser·p0.9999: 19.288 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288222
  mean =      3.325 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11818 
    [ 2.500,  5.000) = 269915 
    [ 5.000,  7.500) = 5236 
    [ 7.500, 10.000) = 741 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 186 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     16.466 ms/op
     p(99.9900) =     19.929 ms/op
     p(99.9990) =     21.957 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.164 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.009 ms/op
Iteration   1: 3.215 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  10.076 ms/op
                 existUser·p0.9999: 20.744 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 3.372 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  19.857 ms/op
                 existUser·p0.9999: 24.134 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   3: 3.606 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  9.485 ms/op
                 existUser·p0.9999: 28.390 ms/op
                 existUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283119
  mean =      3.390 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12490 
    [ 2.500,  5.000) = 263922 
    [ 5.000,  7.500) = 5424 
    [ 7.500, 10.000) = 971 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     26.466 ms/op
     p(99.9990) =     28.973 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.699 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.012 ms/op
Iteration   1: 3.438 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  17.990 ms/op
                 getUser·p0.9999: 27.790 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   2: 3.345 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.257 ms/op
                 getUser·p0.999:  10.376 ms/op
                 getUser·p0.9999: 20.307 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   3: 3.388 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   7.152 ms/op
                 getUser·p0.999:  19.739 ms/op
                 getUser·p0.9999: 25.086 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283047
  mean =      3.390 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11789 
    [ 2.500,  5.000) = 260347 
    [ 5.000,  7.500) = 9073 
    [ 7.500, 10.000) = 1237 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     14.974 ms/op
     p(99.9900) =     27.089 ms/op
     p(99.9990) =     28.868 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.410 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.011 ms/op
Iteration   1: 3.920 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.913 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 21.292 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   2: 3.794 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.698 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.823 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 15.761 ms/op
                 listUser·p1.00:   15.827 ms/op

Iteration   3: 3.837 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.371 ms/op
                 listUser·p0.999:  15.976 ms/op
                 listUser·p0.9999: 19.476 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249156
  mean =      3.850 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 241811 
    [ 5.000,  7.500) = 4938 
    [ 7.500, 10.000) = 1496 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 311 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      7.393 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     21.611 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.594 ± 2.198  ops/ms
ClientPb.existUser                       thrpt       3  10.184 ± 6.167  ops/ms
ClientPb.getUser                         thrpt       3   9.986 ± 4.666  ops/ms
ClientPb.listUser                        thrpt       3   8.335 ± 2.369  ops/ms
ClientPb.createUser                       avgt       3   3.202 ± 0.852   ms/op
ClientPb.existUser                        avgt       3   3.103 ± 1.027   ms/op
ClientPb.getUser                          avgt       3   3.243 ± 0.731   ms/op
ClientPb.listUser                         avgt       3   3.788 ± 1.607   ms/op
ClientPb.createUser                     sample  288222   3.325 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.976           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.466           ms/op
ClientPb.createUser:createUser·p0.9999  sample          19.929           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.429           ms/op
ClientPb.existUser                      sample  283119   3.390 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.325           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.301           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.226           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.485           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.466           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.229           ms/op
ClientPb.getUser                        sample  283047   3.390 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.124           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.974           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.089           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.179           ms/op
ClientPb.listUser                       sample  249156   3.850 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.571           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.162           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.393           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.943           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.857           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.660           ms/op
