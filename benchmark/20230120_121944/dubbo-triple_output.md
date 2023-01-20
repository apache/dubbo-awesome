# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.253 ops/ms
# Warmup Iteration   2: 5.344 ops/ms
# Warmup Iteration   3: 9.392 ops/ms
Iteration   1: 9.801 ops/ms
Iteration   2: 9.544 ops/ms
Iteration   3: 9.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.660 ±(99.9%) 2.381 ops/ms [Average]
  (min, avg, max) = (9.544, 9.660, 9.801), stdev = 0.131
  CI (99.9%): [7.279, 12.041] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.262 ops/ms
# Warmup Iteration   2: 9.402 ops/ms
# Warmup Iteration   3: 10.496 ops/ms
Iteration   1: 10.731 ops/ms
Iteration   2: 10.047 ops/ms
Iteration   3: 10.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.453 ±(99.9%) 6.557 ops/ms [Average]
  (min, avg, max) = (10.047, 10.453, 10.731), stdev = 0.359
  CI (99.9%): [3.897, 17.010] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.163 ops/ms
# Warmup Iteration   2: 8.983 ops/ms
# Warmup Iteration   3: 9.984 ops/ms
Iteration   1: 9.538 ops/ms
Iteration   2: 9.978 ops/ms
Iteration   3: 9.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.813 ±(99.9%) 4.375 ops/ms [Average]
  (min, avg, max) = (9.538, 9.813, 9.978), stdev = 0.240
  CI (99.9%): [5.438, 14.189] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.569 ops/ms
# Warmup Iteration   2: 8.100 ops/ms
# Warmup Iteration   3: 8.587 ops/ms
Iteration   1: 8.738 ops/ms
Iteration   2: 8.401 ops/ms
Iteration   3: 8.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.584 ±(99.9%) 3.112 ops/ms [Average]
  (min, avg, max) = (8.401, 8.584, 8.738), stdev = 0.171
  CI (99.9%): [5.472, 11.696] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.420 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.003 ms/op
Iteration   1: 3.164 ±(99.9%) 0.004 ms/op
Iteration   2: 3.122 ±(99.9%) 0.010 ms/op
Iteration   3: 3.111 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.132 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.111, 3.132, 3.164), stdev = 0.028
  CI (99.9%): [2.622, 3.642] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.725 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.364 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.005 ms/op
Iteration   1: 3.130 ±(99.9%) 0.007 ms/op
Iteration   2: 3.060 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.066 ±(99.9%) 1.121 ms/op [Average]
  (min, avg, max) = (3.007, 3.066, 3.130), stdev = 0.061
  CI (99.9%): [1.945, 4.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.794 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.508 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.004 ms/op
Iteration   1: 3.101 ±(99.9%) 0.003 ms/op
Iteration   2: 3.158 ±(99.9%) 0.006 ms/op
Iteration   3: 3.093 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.118 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (3.093, 3.118, 3.158), stdev = 0.036
  CI (99.9%): [2.467, 3.768] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.125 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.009 ms/op
Iteration   1: 3.645 ±(99.9%) 0.008 ms/op
Iteration   2: 3.879 ±(99.9%) 0.006 ms/op
Iteration   3: 3.762 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.762 ±(99.9%) 2.138 ms/op [Average]
  (min, avg, max) = (3.645, 3.762, 3.879), stdev = 0.117
  CI (99.9%): [1.624, 5.900] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.344 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.009 ms/op
Iteration   1: 3.224 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  13.353 ms/op
                 createUser·p0.9999: 22.154 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.269 ms/op
                 createUser·p0.95:   3.326 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  15.352 ms/op
                 createUser·p0.9999: 21.193 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   3: 3.238 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  12.902 ms/op
                 createUser·p0.9999: 17.740 ms/op
                 createUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300329
  mean =      3.195 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28462 
    [ 2.500,  5.000) = 266315 
    [ 5.000,  7.500) = 4901 
    [ 7.500, 10.000) = 182 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     21.298 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.288 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.008 ms/op
Iteration   1: 3.174 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.415 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  7.954 ms/op
                 existUser·p0.9999: 19.820 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 3.154 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  8.258 ms/op
                 existUser·p0.9999: 26.471 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.186 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  7.928 ms/op
                 existUser·p0.9999: 19.988 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302549
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27006 
    [ 2.500,  5.000) = 268677 
    [ 5.000,  7.500) = 6402 
    [ 7.500, 10.000) = 181 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      8.107 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     26.738 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.865 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
Iteration   1: 3.157 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  15.925 ms/op
                 getUser·p0.9999: 23.191 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 25.170 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.862 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   4.120 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  10.462 ms/op
                 getUser·p0.9999: 23.179 ms/op
                 getUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299310
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13268 
    [ 2.500,  5.000) = 278363 
    [ 5.000,  7.500) = 6814 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     25.597 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.207 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.011 ms/op
Iteration   1: 3.800 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.712 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   2: 3.720 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 16.286 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   3: 3.584 ±(99.9%) 0.006 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   3.711 ms/op
                 listUser·p0.95:   3.895 ms/op
                 listUser·p0.99:   6.021 ms/op
                 listUser·p0.999:  11.957 ms/op
                 listUser·p0.9999: 16.271 ms/op
                 listUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259383
  mean =      3.700 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 252418 
    [ 5.000,  7.500) = 4994 
    [ 7.500, 10.000) = 1229 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.573 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.924 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.660 ± 2.381  ops/ms
ClientPb.existUser                       thrpt       3  10.453 ± 6.557  ops/ms
ClientPb.getUser                         thrpt       3   9.813 ± 4.375  ops/ms
ClientPb.listUser                        thrpt       3   8.584 ± 3.112  ops/ms
ClientPb.createUser                       avgt       3   3.132 ± 0.510   ms/op
ClientPb.existUser                        avgt       3   3.066 ± 1.121   ms/op
ClientPb.getUser                          avgt       3   3.118 ± 0.650   ms/op
ClientPb.listUser                         avgt       3   3.762 ± 2.138   ms/op
ClientPb.createUser                     sample  300329   3.195 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.756           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.523           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.337           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.298           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.724           ms/op
ClientPb.existUser                      sample  302549   3.171 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.896           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.107           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.330           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903           ms/op
ClientPb.getUser                        sample  299310   3.206 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.262           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.539           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.997           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.713           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.117           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.968           ms/op
ClientPb.listUser                       sample  259383   3.700 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.573           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.924           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.353           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.137           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.480           ms/op
