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
# Warmup Iteration   1: 2.439 ops/ms
# Warmup Iteration   2: 6.420 ops/ms
# Warmup Iteration   3: 9.233 ops/ms
Iteration   1: 9.896 ops/ms
Iteration   2: 9.930 ops/ms
Iteration   3: 9.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.882 ±(99.9%) 1.013 ops/ms [Average]
  (min, avg, max) = (9.821, 9.882, 9.930), stdev = 0.056
  CI (99.9%): [8.869, 10.895] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.598 ops/ms
# Warmup Iteration   2: 9.717 ops/ms
# Warmup Iteration   3: 10.446 ops/ms
Iteration   1: 9.952 ops/ms
Iteration   2: 10.458 ops/ms
Iteration   3: 10.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.247 ±(99.9%) 4.798 ops/ms [Average]
  (min, avg, max) = (9.952, 10.247, 10.458), stdev = 0.263
  CI (99.9%): [5.449, 15.044] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.234 ops/ms
# Warmup Iteration   2: 9.377 ops/ms
# Warmup Iteration   3: 9.683 ops/ms
Iteration   1: 10.001 ops/ms
Iteration   2: 9.970 ops/ms
Iteration   3: 10.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.016 ±(99.9%) 1.015 ops/ms [Average]
  (min, avg, max) = (9.970, 10.016, 10.078), stdev = 0.056
  CI (99.9%): [9.001, 11.031] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.497 ops/ms
# Warmup Iteration   2: 7.903 ops/ms
# Warmup Iteration   3: 8.414 ops/ms
Iteration   1: 8.453 ops/ms
Iteration   2: 8.520 ops/ms
Iteration   3: 8.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.457 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (8.399, 8.457, 8.520), stdev = 0.060
  CI (99.9%): [7.359, 9.556] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.657 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.005 ms/op
Iteration   1: 3.309 ±(99.9%) 0.003 ms/op
Iteration   2: 3.257 ±(99.9%) 0.003 ms/op
Iteration   3: 3.226 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.264 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (3.226, 3.264, 3.309), stdev = 0.042
  CI (99.9%): [2.491, 4.037] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.072 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.306 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.001 ms/op
Iteration   1: 3.171 ±(99.9%) 0.003 ms/op
Iteration   2: 3.043 ±(99.9%) 0.002 ms/op
Iteration   3: 3.141 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.118 ±(99.9%) 1.222 ms/op [Average]
  (min, avg, max) = (3.043, 3.118, 3.171), stdev = 0.067
  CI (99.9%): [1.896, 4.340] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.307 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.004 ms/op
Iteration   1: 3.211 ±(99.9%) 0.003 ms/op
Iteration   2: 3.154 ±(99.9%) 0.003 ms/op
Iteration   3: 3.170 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.178 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (3.154, 3.178, 3.211), stdev = 0.029
  CI (99.9%): [2.645, 3.711] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.664 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.006 ms/op
Iteration   1: 3.776 ±(99.9%) 0.005 ms/op
Iteration   2: 3.781 ±(99.9%) 0.003 ms/op
Iteration   3: 3.754 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.770 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.754, 3.770, 3.781), stdev = 0.014
  CI (99.9%): [3.509, 4.032] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.693 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.009 ms/op
Iteration   1: 3.204 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  15.961 ms/op
                 createUser·p0.9999: 18.809 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   2: 3.235 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  12.737 ms/op
                 createUser·p0.9999: 21.053 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   3: 3.217 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  17.112 ms/op
                 createUser·p0.9999: 19.339 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298009
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16170 
    [ 2.500,  5.000) = 277160 
    [ 5.000,  7.500) = 3515 
    [ 7.500, 10.000) = 456 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 176 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     16.940 ms/op
     p(99.9900) =     20.480 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.319 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.338 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.007 ms/op
Iteration   1: 3.068 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.442 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  11.956 ms/op
                 existUser·p0.9999: 20.532 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   2: 3.143 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  11.747 ms/op
                 existUser·p0.9999: 20.939 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   5.814 ms/op
                 existUser·p0.999:  12.567 ms/op
                 existUser·p0.9999: 20.410 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306814
  mean =      3.128 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17956 
    [ 2.500,  5.000) = 283868 
    [ 5.000,  7.500) = 4113 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 133 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     20.753 ms/op
     p(99.9990) =     21.452 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.105 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.339 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
Iteration   1: 3.240 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  17.082 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   2: 3.211 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  13.608 ms/op
                 getUser·p0.9999: 20.840 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   3: 3.252 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  13.487 ms/op
                 getUser·p0.9999: 18.192 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296698
  mean =      3.234 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12870 
    [ 2.500,  5.000) = 278406 
    [ 5.000,  7.500) = 4572 
    [ 7.500, 10.000) = 338 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     23.894 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 8.503 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.011 ms/op
Iteration   1: 3.792 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  13.806 ms/op
                 listUser·p0.9999: 17.978 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 3.804 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.275 ms/op
                 listUser·p0.999:  12.403 ms/op
                 listUser·p0.9999: 14.631 ms/op
                 listUser·p1.00:   15.843 ms/op

Iteration   3: 3.810 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.332 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 14.493 ms/op
                 listUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252456
  mean =      3.802 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 103 
    [ 2.500,  3.750) = 133812 
    [ 3.750,  5.000) = 112595 
    [ 5.000,  6.250) = 3107 
    [ 6.250,  7.500) = 1716 
    [ 7.500,  8.750) = 307 
    [ 8.750, 10.000) = 170 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 177 
    [12.500, 13.750) = 187 
    [13.750, 15.000) = 94 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     13.001 ms/op
     p(99.9900) =     16.810 ms/op
     p(99.9990) =     19.083 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.882 ± 1.013  ops/ms
ClientPb.existUser                       thrpt       3  10.247 ± 4.798  ops/ms
ClientPb.getUser                         thrpt       3  10.016 ± 1.015  ops/ms
ClientPb.listUser                        thrpt       3   8.457 ± 1.099  ops/ms
ClientPb.createUser                       avgt       3   3.264 ± 0.773   ms/op
ClientPb.existUser                        avgt       3   3.118 ± 1.222   ms/op
ClientPb.getUser                          avgt       3   3.178 ± 0.533   ms/op
ClientPb.listUser                         avgt       3   3.770 ± 0.262   ms/op
ClientPb.createUser                     sample  298009   3.218 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.079           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.940           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.480           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.725           ms/op
ClientPb.existUser                      sample  306814   3.128 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.303           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.567           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.753           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.496           ms/op
ClientPb.getUser                        sample  296698   3.234 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.722           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.564           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.286           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.299           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.510           ms/op
ClientPb.listUser                       sample  252456   3.802 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.720           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.390           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.001           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.810           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.268           ms/op
