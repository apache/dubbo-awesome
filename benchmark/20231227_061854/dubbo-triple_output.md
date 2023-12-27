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
# Warmup Iteration   1: 4.949 ops/ms
# Warmup Iteration   2: 12.320 ops/ms
# Warmup Iteration   3: 12.579 ops/ms
Iteration   1: 12.735 ops/ms
Iteration   2: 12.861 ops/ms
Iteration   3: 12.871 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.823 ±(99.9%) 1.383 ops/ms [Average]
  (min, avg, max) = (12.735, 12.823, 12.871), stdev = 0.076
  CI (99.9%): [11.439, 14.206] (assumes normal distribution)


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
# Warmup Iteration   1: 8.142 ops/ms
# Warmup Iteration   2: 13.216 ops/ms
# Warmup Iteration   3: 13.310 ops/ms
Iteration   1: 13.270 ops/ms
Iteration   2: 13.321 ops/ms
Iteration   3: 13.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.306 ±(99.9%) 0.576 ops/ms [Average]
  (min, avg, max) = (13.270, 13.306, 13.327), stdev = 0.032
  CI (99.9%): [12.730, 13.882] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.501 ops/ms
# Warmup Iteration   2: 12.528 ops/ms
# Warmup Iteration   3: 12.701 ops/ms
Iteration   1: 12.854 ops/ms
Iteration   2: 12.820 ops/ms
Iteration   3: 12.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.842 ±(99.9%) 0.359 ops/ms [Average]
  (min, avg, max) = (12.820, 12.842, 12.854), stdev = 0.020
  CI (99.9%): [12.483, 13.202] (assumes normal distribution)


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
# Warmup Iteration   1: 6.378 ops/ms
# Warmup Iteration   2: 10.592 ops/ms
# Warmup Iteration   3: 10.681 ops/ms
Iteration   1: 10.806 ops/ms
Iteration   2: 10.849 ops/ms
Iteration   3: 10.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.822 ±(99.9%) 0.422 ops/ms [Average]
  (min, avg, max) = (10.806, 10.822, 10.849), stdev = 0.023
  CI (99.9%): [10.400, 11.245] (assumes normal distribution)


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.508 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.500, 2.508, 2.514), stdev = 0.007
  CI (99.9%): [2.377, 2.639] (assumes normal distribution)


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
# Warmup Iteration   1: 3.544 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.004 ms/op
Iteration   1: 2.455 ±(99.9%) 0.003 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.445 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.431, 2.445, 2.455), stdev = 0.012
  CI (99.9%): [2.223, 2.666] (assumes normal distribution)


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.004 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.417 ±(99.9%) 0.117 ms/op [Average]
  (min, avg, max) = (2.412, 2.417, 2.424), stdev = 0.006
  CI (99.9%): [2.301, 2.534] (assumes normal distribution)


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
# Warmup Iteration   1: 4.540 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.004 ms/op
Iteration   1: 2.951 ±(99.9%) 0.005 ms/op
Iteration   2: 2.932 ±(99.9%) 0.006 ms/op
Iteration   3: 2.970 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.951 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (2.932, 2.951, 2.970), stdev = 0.019
  CI (99.9%): [2.603, 3.299] (assumes normal distribution)


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
Iteration   1: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.674 ms/op
                 createUser·p0.999:  11.377 ms/op
                 createUser·p0.9999: 13.271 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.543 ms/op
                 createUser·p0.999:  8.878 ms/op
                 createUser·p0.9999: 11.549 ms/op
                 createUser·p1.00:   12.534 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  8.369 ms/op
                 createUser·p0.9999: 11.174 ms/op
                 createUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380459
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 183635 
    [ 2.500,  3.750) = 193365 
    [ 3.750,  5.000) = 2684 
    [ 5.000,  6.250) = 291 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      8.377 ms/op
     p(99.9900) =     12.860 ms/op
     p(99.9990) =     13.677 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 3.595 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.351 ms/op
                 existUser·p0.999:  6.013 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  7.078 ms/op
                 existUser·p0.9999: 12.304 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  9.110 ms/op
                 existUser·p0.9999: 12.435 ms/op
                 existUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390938
  mean =      2.453 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 194433 
    [ 2.500,  3.750) = 194214 
    [ 3.750,  5.000) = 1638 
    [ 5.000,  6.250) = 170 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.424 ms/op
     p(99.9000) =      8.881 ms/op
     p(99.9900) =     13.171 ms/op
     p(99.9990) =     14.026 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  6.330 ms/op
                 getUser·p0.9999: 13.629 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  7.507 ms/op
                 getUser·p0.9999: 12.027 ms/op
                 getUser·p1.00:   13.631 ms/op

Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  5.984 ms/op
                 getUser·p0.9999: 10.155 ms/op
                 getUser·p1.00:   10.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391795
  mean =      2.448 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 198416 
    [ 2.500,  3.750) = 189399 
    [ 3.750,  5.000) = 3141 
    [ 5.000,  6.250) = 357 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      6.628 ms/op
     p(99.9900) =     13.039 ms/op
     p(99.9990) =     14.520 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 4.543 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
Iteration   1: 3.034 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  9.612 ms/op
                 listUser·p0.9999: 11.337 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   2: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  8.946 ms/op
                 listUser·p0.9999: 11.998 ms/op
                 listUser·p1.00:   14.057 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.700 ms/op
                 listUser·p0.9999: 11.636 ms/op
                 listUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319468
  mean =      3.002 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 95281 
    [ 2.500,  3.750) = 184319 
    [ 3.750,  5.000) = 32268 
    [ 5.000,  6.250) = 5968 
    [ 6.250,  7.500) = 635 
    [ 7.500,  8.750) = 465 
    [ 8.750, 10.000) = 208 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      8.954 ms/op
     p(99.9900) =     11.667 ms/op
     p(99.9990) =     12.581 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.823 ± 1.383  ops/ms
ClientPb.existUser                       thrpt       3  13.306 ± 0.576  ops/ms
ClientPb.getUser                         thrpt       3  12.842 ± 0.359  ops/ms
ClientPb.listUser                        thrpt       3  10.822 ± 0.422  ops/ms
ClientPb.createUser                       avgt       3   2.508 ± 0.131   ms/op
ClientPb.existUser                        avgt       3   2.445 ± 0.221   ms/op
ClientPb.getUser                          avgt       3   2.417 ± 0.117   ms/op
ClientPb.listUser                         avgt       3   2.951 ± 0.348   ms/op
ClientPb.createUser                     sample  380459   2.521 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.694           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.377           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.860           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.910           ms/op
ClientPb.existUser                      sample  390938   2.453 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.823           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.424           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.881           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.171           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.448           ms/op
ClientPb.getUser                        sample  391795   2.448 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.721           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.628           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.039           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.729           ms/op
ClientPb.listUser                       sample  319468   3.002 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.833           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.954           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.667           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.057           ms/op
