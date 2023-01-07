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
# Warmup Iteration   1: 2.795 ops/ms
# Warmup Iteration   2: 6.537 ops/ms
# Warmup Iteration   3: 9.366 ops/ms
Iteration   1: 10.270 ops/ms
Iteration   2: 10.196 ops/ms
Iteration   3: 9.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.060 ±(99.9%) 5.511 ops/ms [Average]
  (min, avg, max) = (9.714, 10.060, 10.270), stdev = 0.302
  CI (99.9%): [4.548, 15.571] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.621 ops/ms
# Warmup Iteration   2: 9.640 ops/ms
# Warmup Iteration   3: 10.384 ops/ms
Iteration   1: 10.260 ops/ms
Iteration   2: 10.336 ops/ms
Iteration   3: 10.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.375 ±(99.9%) 2.524 ops/ms [Average]
  (min, avg, max) = (10.260, 10.375, 10.528), stdev = 0.138
  CI (99.9%): [7.851, 12.899] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.434 ops/ms
# Warmup Iteration   2: 7.855 ops/ms
# Warmup Iteration   3: 10.155 ops/ms
Iteration   1: 9.880 ops/ms
Iteration   2: 10.056 ops/ms
Iteration   3: 10.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.081 ±(99.9%) 3.913 ops/ms [Average]
  (min, avg, max) = (9.880, 10.081, 10.307), stdev = 0.214
  CI (99.9%): [6.168, 13.994] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.190 ops/ms
# Warmup Iteration   2: 7.891 ops/ms
# Warmup Iteration   3: 8.403 ops/ms
Iteration   1: 8.759 ops/ms
Iteration   2: 8.656 ops/ms
Iteration   3: 8.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.653 ±(99.9%) 1.961 ops/ms [Average]
  (min, avg, max) = (8.544, 8.653, 8.759), stdev = 0.107
  CI (99.9%): [6.692, 10.613] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.489 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.416 ±(99.9%) 0.005 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
Iteration   3: 3.066 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.061 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (3.033, 3.061, 3.085), stdev = 0.027
  CI (99.9%): [2.577, 3.546] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.764 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.005 ms/op
Iteration   1: 2.948 ±(99.9%) 0.006 ms/op
Iteration   2: 3.012 ±(99.9%) 0.007 ms/op
Iteration   3: 3.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.991 ±(99.9%) 0.690 ms/op [Average]
  (min, avg, max) = (2.948, 2.991, 3.014), stdev = 0.038
  CI (99.9%): [2.301, 3.682] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.034 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.496 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.003 ms/op
Iteration   1: 3.171 ±(99.9%) 0.004 ms/op
Iteration   2: 3.117 ±(99.9%) 0.008 ms/op
Iteration   3: 3.113 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.134 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.113, 3.134, 3.171), stdev = 0.033
  CI (99.9%): [2.535, 3.732] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.197 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.010 ms/op
Iteration   1: 3.608 ±(99.9%) 0.007 ms/op
Iteration   2: 3.652 ±(99.9%) 0.008 ms/op
Iteration   3: 3.610 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.623 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (3.608, 3.623, 3.652), stdev = 0.025
  CI (99.9%): [3.168, 4.079] (assumes normal distribution)


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
# Warmup Iteration   1: 8.001 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.010 ms/op
Iteration   1: 3.141 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  12.091 ms/op
                 createUser·p0.9999: 22.695 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   2: 3.202 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  11.908 ms/op
                 createUser·p0.9999: 30.441 ms/op
                 createUser·p1.00:   30.966 ms/op

Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  12.485 ms/op
                 createUser·p0.9999: 20.240 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303402
  mean =      3.165 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23079 
    [ 2.500,  5.000) = 274932 
    [ 5.000,  7.500) = 4370 
    [ 7.500, 10.000) = 596 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     29.491 ms/op
     p(99.9990) =     30.474 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.431 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.008 ms/op
Iteration   1: 3.086 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  9.052 ms/op
                 existUser·p0.9999: 19.977 ms/op
                 existUser·p1.00:   21.365 ms/op

Iteration   2: 2.985 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.154 ms/op
                 existUser·p0.95:   3.228 ms/op
                 existUser·p0.99:   4.923 ms/op
                 existUser·p0.999:  9.992 ms/op
                 existUser·p0.9999: 25.128 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  11.631 ms/op
                 existUser·p0.9999: 18.971 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315748
  mean =      3.037 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21556 
    [ 2.500,  5.000) = 289389 
    [ 5.000,  7.500) = 4105 
    [ 7.500, 10.000) = 314 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.211 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     10.986 ms/op
     p(99.9900) =     24.178 ms/op
     p(99.9990) =     25.735 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


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
# Warmup Iteration   1: 8.506 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.009 ms/op
Iteration   1: 3.188 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  10.076 ms/op
                 getUser·p0.9999: 22.281 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   2: 3.129 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.151 ms/op
                 getUser·p0.999:  9.153 ms/op
                 getUser·p0.9999: 21.914 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  12.376 ms/op
                 getUser·p0.9999: 21.094 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305236
  mean =      3.144 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18610 
    [ 2.500,  5.000) = 280793 
    [ 5.000,  7.500) = 4980 
    [ 7.500, 10.000) = 530 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 161 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     11.760 ms/op
     p(99.9900) =     21.937 ms/op
     p(99.9990) =     22.670 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 7.553 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.012 ms/op
Iteration   1: 3.688 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.718 ms/op
                 listUser·p0.9999: 20.513 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 3.738 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.616 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 3.719 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.166 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  12.862 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258262
  mean =      3.715 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 250540 
    [ 5.000,  7.500) = 5877 
    [ 7.500, 10.000) = 1033 
    [10.000, 12.500) = 348 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.745 ms/op
     p(99.9000) =     13.316 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     21.509 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.060 ± 5.511  ops/ms
ClientPb.existUser                       thrpt       3  10.375 ± 2.524  ops/ms
ClientPb.getUser                         thrpt       3  10.081 ± 3.913  ops/ms
ClientPb.listUser                        thrpt       3   8.653 ± 1.961  ops/ms
ClientPb.createUser                       avgt       3   3.061 ± 0.484   ms/op
ClientPb.existUser                        avgt       3   2.991 ± 0.690   ms/op
ClientPb.getUser                          avgt       3   3.134 ± 0.598   ms/op
ClientPb.listUser                         avgt       3   3.623 ± 0.456   ms/op
ClientPb.createUser                     sample  303402   3.165 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.910           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.091           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.491           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.966           ms/op
ClientPb.existUser                      sample  315748   3.037 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.939           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.986           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.178           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.230           ms/op
ClientPb.getUser                        sample  305236   3.144 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.977           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.465           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.760           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.937           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.921           ms/op
ClientPb.listUser                       sample  258262   3.715 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.745           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.316           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.382           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.529           ms/op
