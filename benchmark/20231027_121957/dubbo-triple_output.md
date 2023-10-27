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
# Warmup Iteration   1: 1.366 ops/ms
# Warmup Iteration   2: 3.124 ops/ms
# Warmup Iteration   3: 6.447 ops/ms
Iteration   1: 6.700 ops/ms
Iteration   2: 7.362 ops/ms
Iteration   3: 7.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.230 ±(99.9%) 8.709 ops/ms [Average]
  (min, avg, max) = (6.700, 7.230, 7.627), stdev = 0.477
  CI (99.9%): [≈ 0, 15.938] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.983 ops/ms
# Warmup Iteration   2: 6.303 ops/ms
# Warmup Iteration   3: 7.735 ops/ms
Iteration   1: 7.914 ops/ms
Iteration   2: 7.903 ops/ms
Iteration   3: 7.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.779 ±(99.9%) 4.075 ops/ms [Average]
  (min, avg, max) = (7.522, 7.779, 7.914), stdev = 0.223
  CI (99.9%): [3.704, 11.855] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.974 ops/ms
# Warmup Iteration   2: 5.735 ops/ms
# Warmup Iteration   3: 7.281 ops/ms
Iteration   1: 7.065 ops/ms
Iteration   2: 7.213 ops/ms
Iteration   3: 7.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.303 ±(99.9%) 5.346 ops/ms [Average]
  (min, avg, max) = (7.065, 7.303, 7.630), stdev = 0.293
  CI (99.9%): [1.957, 12.648] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.711 ops/ms
# Warmup Iteration   2: 4.881 ops/ms
# Warmup Iteration   3: 6.376 ops/ms
Iteration   1: 6.362 ops/ms
Iteration   2: 6.348 ops/ms
Iteration   3: 6.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.395 ±(99.9%) 1.266 ops/ms [Average]
  (min, avg, max) = (6.348, 6.395, 6.475), stdev = 0.069
  CI (99.9%): [5.129, 7.661] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 14.081 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.799 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.376 ±(99.9%) 0.003 ms/op
Iteration   1: 4.433 ±(99.9%) 0.008 ms/op
Iteration   2: 4.203 ±(99.9%) 0.003 ms/op
Iteration   3: 4.166 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.267 ±(99.9%) 2.647 ms/op [Average]
  (min, avg, max) = (4.166, 4.267, 4.433), stdev = 0.145
  CI (99.9%): [1.620, 6.914] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.766 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.703 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.004 ms/op
Iteration   1: 4.074 ±(99.9%) 0.005 ms/op
Iteration   2: 4.042 ±(99.9%) 0.006 ms/op
Iteration   3: 4.055 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.057 ±(99.9%) 0.297 ms/op [Average]
  (min, avg, max) = (4.042, 4.057, 4.074), stdev = 0.016
  CI (99.9%): [3.760, 4.354] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.448 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.967 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.407 ±(99.9%) 0.004 ms/op
Iteration   1: 4.278 ±(99.9%) 0.004 ms/op
Iteration   2: 4.125 ±(99.9%) 0.008 ms/op
Iteration   3: 4.252 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.219 ±(99.9%) 1.495 ms/op [Average]
  (min, avg, max) = (4.125, 4.219, 4.278), stdev = 0.082
  CI (99.9%): [2.724, 5.713] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 14.735 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.115 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.081 ±(99.9%) 0.011 ms/op
Iteration   1: 4.902 ±(99.9%) 0.008 ms/op
Iteration   2: 4.932 ±(99.9%) 0.007 ms/op
Iteration   3: 4.895 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.910 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (4.895, 4.910, 4.932), stdev = 0.020
  CI (99.9%): [4.549, 5.271] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 15.379 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.566 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 4.617 ±(99.9%) 0.019 ms/op
Iteration   1: 4.272 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.763 ms/op
                 createUser·p0.50:   4.145 ms/op
                 createUser·p0.90:   4.948 ms/op
                 createUser·p0.95:   5.448 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  13.021 ms/op
                 createUser·p0.9999: 27.001 ms/op
                 createUser·p1.00:   30.474 ms/op

Iteration   2: 4.117 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.640 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  25.614 ms/op
                 createUser·p0.9999: 28.450 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   3: 4.170 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.152 ms/op
                 createUser·p0.99:   7.898 ms/op
                 createUser·p0.999:  14.428 ms/op
                 createUser·p0.9999: 32.156 ms/op
                 createUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 229198
  mean =      4.185 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 220 
    [ 2.500,  5.000) = 213150 
    [ 5.000,  7.500) = 13889 
    [ 7.500, 10.000) = 1319 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     16.220 ms/op
     p(99.9900) =     30.510 ms/op
     p(99.9990) =     33.081 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 12.596 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 4.466 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.012 ms/op
Iteration   1: 4.049 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  22.053 ms/op
                 existUser·p0.9999: 24.838 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 4.084 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.001 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  13.102 ms/op
                 existUser·p0.9999: 26.116 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 4.082 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.804 ms/op
                 existUser·p0.50:   3.981 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   7.700 ms/op
                 existUser·p0.999:  17.334 ms/op
                 existUser·p0.9999: 28.746 ms/op
                 existUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 235792
  mean =      4.072 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 250 
    [ 2.500,  5.000) = 223969 
    [ 5.000,  7.500) = 9498 
    [ 7.500, 10.000) = 1439 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     17.477 ms/op
     p(99.9900) =     27.736 ms/op
     p(99.9990) =     29.449 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 12.548 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.825 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.424 ±(99.9%) 0.014 ms/op
Iteration   1: 4.319 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.776 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   9.028 ms/op
                 getUser·p0.999:  23.091 ms/op
                 getUser·p0.9999: 31.097 ms/op
                 getUser·p1.00:   31.359 ms/op

Iteration   2: 4.143 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.683 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  9.978 ms/op
                 getUser·p0.9999: 25.732 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 4.252 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   8.995 ms/op
                 getUser·p0.999:  17.245 ms/op
                 getUser·p0.9999: 27.574 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 226505
  mean =      4.237 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 213454 
    [ 5.000,  7.500) = 8730 
    [ 7.500, 10.000) = 3143 
    [10.000, 12.500) = 616 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     21.396 ms/op
     p(99.9900) =     30.584 ms/op
     p(99.9990) =     31.318 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.580 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 6.663 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.269 ±(99.9%) 0.020 ms/op
Iteration   1: 5.117 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   5.652 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  26.804 ms/op
                 listUser·p0.9999: 29.680 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   2: 5.116 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  25.297 ms/op
                 listUser·p0.9999: 34.702 ms/op
                 listUser·p1.00:   35.652 ms/op

Iteration   3: 4.865 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  17.768 ms/op
                 listUser·p0.9999: 20.756 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 190770
  mean =      5.030 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 120450 
    [ 5.000,  7.500) = 66084 
    [ 7.500, 10.000) = 2920 
    [10.000, 12.500) = 563 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.552 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     23.953 ms/op
     p(99.9900) =     30.210 ms/op
     p(99.9990) =     35.592 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.230 ± 8.709  ops/ms
ClientPb.existUser                       thrpt       3   7.779 ± 4.075  ops/ms
ClientPb.getUser                         thrpt       3   7.303 ± 5.346  ops/ms
ClientPb.listUser                        thrpt       3   6.395 ± 1.266  ops/ms
ClientPb.createUser                       avgt       3   4.267 ± 2.647   ms/op
ClientPb.existUser                        avgt       3   4.057 ± 0.297   ms/op
ClientPb.getUser                          avgt       3   4.219 ± 1.495   ms/op
ClientPb.listUser                         avgt       3   4.910 ± 0.361   ms/op
ClientPb.createUser                     sample  229198   4.185 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.389           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.242           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.220           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.510           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.358           ms/op
ClientPb.existUser                      sample  235792   4.072 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.380           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.961           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.315           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.477           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.736           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.884           ms/op
ClientPb.getUser                        sample  226505   4.237 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.268           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.177           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.471           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.396           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.584           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.359           ms/op
ClientPb.listUser                       sample  190770   5.030 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.552           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.044           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.953           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.210           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.652           ms/op
