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
# Warmup Iteration   1: 2.392 ops/ms
# Warmup Iteration   2: 6.396 ops/ms
# Warmup Iteration   3: 9.121 ops/ms
Iteration   1: 9.793 ops/ms
Iteration   2: 10.028 ops/ms
Iteration   3: 9.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.940 ±(99.9%) 2.336 ops/ms [Average]
  (min, avg, max) = (9.793, 9.940, 10.028), stdev = 0.128
  CI (99.9%): [7.604, 12.276] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.475 ops/ms
# Warmup Iteration   2: 9.261 ops/ms
# Warmup Iteration   3: 9.788 ops/ms
Iteration   1: 10.485 ops/ms
Iteration   2: 10.190 ops/ms
Iteration   3: 9.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.172 ±(99.9%) 5.893 ops/ms [Average]
  (min, avg, max) = (9.840, 10.172, 10.485), stdev = 0.323
  CI (99.9%): [4.279, 16.065] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.446 ops/ms
# Warmup Iteration   2: 8.776 ops/ms
# Warmup Iteration   3: 9.593 ops/ms
Iteration   1: 10.053 ops/ms
Iteration   2: 9.650 ops/ms
Iteration   3: 9.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.761 ±(99.9%) 4.669 ops/ms [Average]
  (min, avg, max) = (9.579, 9.761, 10.053), stdev = 0.256
  CI (99.9%): [5.091, 14.430] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.230 ops/ms
# Warmup Iteration   2: 7.820 ops/ms
# Warmup Iteration   3: 8.373 ops/ms
Iteration   1: 8.295 ops/ms
Iteration   2: 8.574 ops/ms
Iteration   3: 8.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.513 ±(99.9%) 3.547 ops/ms [Average]
  (min, avg, max) = (8.295, 8.513, 8.670), stdev = 0.194
  CI (99.9%): [4.966, 12.060] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.944 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.010 ms/op
Iteration   1: 3.251 ±(99.9%) 0.002 ms/op
Iteration   2: 3.280 ±(99.9%) 0.008 ms/op
Iteration   3: 3.220 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.250 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (3.220, 3.250, 3.280), stdev = 0.030
  CI (99.9%): [2.700, 3.801] (assumes normal distribution)


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
# Warmup Iteration   1: 7.136 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.390 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
Iteration   2: 3.102 ±(99.9%) 0.004 ms/op
Iteration   3: 3.144 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.090 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (3.023, 3.090, 3.144), stdev = 0.062
  CI (99.9%): [1.966, 4.213] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.115 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.005 ms/op
Iteration   1: 3.169 ±(99.9%) 0.003 ms/op
Iteration   2: 3.185 ±(99.9%) 0.005 ms/op
Iteration   3: 3.382 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.245 ±(99.9%) 2.168 ms/op [Average]
  (min, avg, max) = (3.169, 3.245, 3.382), stdev = 0.119
  CI (99.9%): [1.077, 5.413] (assumes normal distribution)


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
# Warmup Iteration   1: 8.973 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.005 ms/op
Iteration   1: 3.818 ±(99.9%) 0.011 ms/op
Iteration   2: 3.896 ±(99.9%) 0.008 ms/op
Iteration   3: 3.724 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.813 ±(99.9%) 1.579 ms/op [Average]
  (min, avg, max) = (3.724, 3.813, 3.896), stdev = 0.087
  CI (99.9%): [2.234, 5.392] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.036 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.680 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
Iteration   1: 3.269 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  13.199 ms/op
                 createUser·p0.9999: 27.562 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   2: 3.266 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.232 ms/op
                 createUser·p0.999:  17.400 ms/op
                 createUser·p0.9999: 23.764 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.787 ms/op
                 createUser·p0.999:  14.555 ms/op
                 createUser·p0.9999: 23.478 ms/op
                 createUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293901
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14956 
    [ 2.500,  5.000) = 271565 
    [ 5.000,  7.500) = 6005 
    [ 7.500, 10.000) = 961 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     25.907 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 7.513 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.008 ms/op
Iteration   1: 3.111 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  13.910 ms/op
                 existUser·p0.9999: 24.993 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   2: 3.155 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.041 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  11.087 ms/op
                 existUser·p0.9999: 22.920 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  12.600 ms/op
                 existUser·p0.9999: 25.675 ms/op
                 existUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308590
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19133 
    [ 2.500,  5.000) = 283970 
    [ 5.000,  7.500) = 4752 
    [ 7.500, 10.000) = 335 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     13.087 ms/op
     p(99.9900) =     24.744 ms/op
     p(99.9990) =     28.077 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 8.302 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.009 ms/op
Iteration   1: 3.371 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.681 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  19.374 ms/op
                 getUser·p0.9999: 24.414 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.786 ms/op
                 getUser·p0.999:  9.770 ms/op
                 getUser·p0.9999: 24.108 ms/op
                 getUser·p1.00:   25.231 ms/op

Iteration   3: 3.301 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 22.512 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292284
  mean =      3.281 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25587 
    [ 2.500,  5.000) = 258006 
    [ 5.000,  7.500) = 7705 
    [ 7.500, 10.000) = 593 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     25.249 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 9.898 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.013 ms/op
Iteration   1: 3.754 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  19.235 ms/op
                 listUser·p0.9999: 24.356 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   2: 3.871 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.544 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  12.288 ms/op
                 listUser·p0.9999: 14.479 ms/op
                 listUser·p1.00:   14.549 ms/op

Iteration   3: 3.767 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  12.681 ms/op
                 listUser·p0.9999: 19.350 ms/op
                 listUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252775
  mean =      3.797 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 98 
    [ 2.500,  5.000) = 243645 
    [ 5.000,  7.500) = 6532 
    [ 7.500, 10.000) = 1663 
    [10.000, 12.500) = 503 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     13.369 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     25.262 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.940 ± 2.336  ops/ms
ClientPb.existUser                       thrpt       3  10.172 ± 5.893  ops/ms
ClientPb.getUser                         thrpt       3   9.761 ± 4.669  ops/ms
ClientPb.listUser                        thrpt       3   8.513 ± 3.547  ops/ms
ClientPb.createUser                       avgt       3   3.250 ± 0.551   ms/op
ClientPb.existUser                        avgt       3   3.090 ± 1.123   ms/op
ClientPb.getUser                          avgt       3   3.245 ± 2.168   ms/op
ClientPb.listUser                         avgt       3   3.813 ± 1.579   ms/op
ClientPb.createUser                     sample  293901   3.263 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.947           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.193           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.138           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.907           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.639           ms/op
ClientPb.existUser                      sample  308590   3.109 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.920           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.087           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.744           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.246           ms/op
ClientPb.getUser                        sample  292284   3.281 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.283           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.039           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.888           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.559           ms/op
ClientPb.listUser                       sample  252775   3.797 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.544           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.479           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.369           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.396           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.985           ms/op
