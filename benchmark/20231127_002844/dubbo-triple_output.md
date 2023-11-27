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
# Warmup Iteration   1: 4.867 ops/ms
# Warmup Iteration   2: 12.011 ops/ms
# Warmup Iteration   3: 12.402 ops/ms
Iteration   1: 12.494 ops/ms
Iteration   2: 12.595 ops/ms
Iteration   3: 12.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.613 ±(99.9%) 2.348 ops/ms [Average]
  (min, avg, max) = (12.494, 12.613, 12.750), stdev = 0.129
  CI (99.9%): [10.266, 14.961] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.633 ops/ms
# Warmup Iteration   2: 12.765 ops/ms
# Warmup Iteration   3: 12.918 ops/ms
Iteration   1: 12.918 ops/ms
Iteration   2: 12.912 ops/ms
Iteration   3: 12.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.919 ±(99.9%) 0.163 ops/ms [Average]
  (min, avg, max) = (12.912, 12.919, 12.929), stdev = 0.009
  CI (99.9%): [12.756, 13.083] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.274 ops/ms
# Warmup Iteration   2: 12.419 ops/ms
# Warmup Iteration   3: 12.676 ops/ms
Iteration   1: 12.832 ops/ms
Iteration   2: 12.691 ops/ms
Iteration   3: 12.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.755 ±(99.9%) 1.307 ops/ms [Average]
  (min, avg, max) = (12.691, 12.755, 12.832), stdev = 0.072
  CI (99.9%): [11.448, 14.062] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.406 ops/ms
# Warmup Iteration   2: 10.273 ops/ms
# Warmup Iteration   3: 10.526 ops/ms
Iteration   1: 10.362 ops/ms
Iteration   2: 10.571 ops/ms
Iteration   3: 10.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.484 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (10.362, 10.484, 10.571), stdev = 0.109
  CI (99.9%): [8.498, 12.470] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.020 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
Iteration   1: 2.592 ±(99.9%) 0.005 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.521 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.556 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (2.521, 2.556, 2.592), stdev = 0.035
  CI (99.9%): [1.909, 3.204] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.003 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.479 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.470, 2.479, 2.490), stdev = 0.010
  CI (99.9%): [2.293, 2.664] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.581 ±(99.9%) 0.005 ms/op
Iteration   1: 2.567 ±(99.9%) 0.005 ms/op
Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
Iteration   3: 2.589 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.569 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.550, 2.569, 2.589), stdev = 0.020
  CI (99.9%): [2.208, 2.929] (assumes normal distribution)


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
# Warmup Iteration   1: 4.547 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.005 ms/op
Iteration   1: 3.009 ±(99.9%) 0.005 ms/op
Iteration   2: 3.018 ±(99.9%) 0.005 ms/op
Iteration   3: 2.998 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.008 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (2.998, 3.008, 3.018), stdev = 0.010
  CI (99.9%): [2.830, 3.186] (assumes normal distribution)


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.695 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.549 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  11.846 ms/op
                 createUser·p0.9999: 13.914 ms/op
                 createUser·p1.00:   15.024 ms/op

Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  9.535 ms/op
                 createUser·p0.9999: 12.583 ms/op
                 createUser·p1.00:   13.189 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  8.495 ms/op
                 createUser·p0.9999: 10.435 ms/op
                 createUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377091
  mean =      2.544 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 181006 
    [ 2.500,  3.750) = 191442 
    [ 3.750,  5.000) = 3521 
    [ 5.000,  6.250) = 575 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     14.848 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   2.671 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  11.321 ms/op
                 existUser·p0.9999: 13.631 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.149 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.152 ms/op
                 existUser·p0.99:   3.689 ms/op
                 existUser·p0.999:  6.344 ms/op
                 existUser·p0.9999: 12.407 ms/op
                 existUser·p1.00:   12.550 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.642 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.503 ms/op
                 existUser·p0.9999: 11.207 ms/op
                 existUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 380576
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 182995 
    [ 2.500,  3.750) = 193311 
    [ 3.750,  5.000) = 3185 
    [ 5.000,  6.250) = 593 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      7.266 ms/op
     p(99.9900) =     12.927 ms/op
     p(99.9990) =     13.821 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  10.604 ms/op
                 getUser·p0.9999: 14.150 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   2: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  6.481 ms/op
                 getUser·p0.9999: 11.246 ms/op
                 getUser·p1.00:   12.141 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  8.069 ms/op
                 getUser·p0.9999: 11.573 ms/op
                 getUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379856
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 186151 
    [ 2.500,  3.750) = 187254 
    [ 3.750,  5.000) = 4655 
    [ 5.000,  6.250) = 1237 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.751 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     14.333 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 4.547 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.009 ms/op
Iteration   1: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.868 ms/op
                 listUser·p0.9999: 10.715 ms/op
                 listUser·p1.00:   13.058 ms/op

Iteration   2: 3.049 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.653 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   5.882 ms/op
                 listUser·p0.999:  9.880 ms/op
                 listUser·p0.9999: 13.026 ms/op
                 listUser·p1.00:   13.582 ms/op

Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.048 ms/op
                 listUser·p0.9999: 11.361 ms/op
                 listUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317349
  mean =      3.023 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 94317 
    [ 2.500,  3.750) = 181366 
    [ 3.750,  5.000) = 32982 
    [ 5.000,  6.250) = 6864 
    [ 6.250,  7.500) = 945 
    [ 7.500,  8.750) = 309 
    [ 8.750, 10.000) = 247 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.317 ms/op
     p(99.9900) =     11.899 ms/op
     p(99.9990) =     13.579 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.613 ± 2.348  ops/ms
ClientPb.existUser                       thrpt       3  12.919 ± 0.163  ops/ms
ClientPb.getUser                         thrpt       3  12.755 ± 1.307  ops/ms
ClientPb.listUser                        thrpt       3  10.484 ± 1.986  ops/ms
ClientPb.createUser                       avgt       3   2.556 ± 0.648   ms/op
ClientPb.existUser                        avgt       3   2.479 ± 0.186   ms/op
ClientPb.getUser                          avgt       3   2.569 ± 0.360   ms/op
ClientPb.listUser                         avgt       3   3.008 ± 0.178   ms/op
ClientPb.createUser                     sample  377091   2.544 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.962           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.175           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.550           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.024           ms/op
ClientPb.existUser                      sample  380576   2.520 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.862           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.630           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.266           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.927           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.992           ms/op
ClientPb.getUser                        sample  379856   2.525 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.783           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.751           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.353           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.647           ms/op
ClientPb.listUser                       sample  317349   3.023 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.653           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.317           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.899           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.582           ms/op
